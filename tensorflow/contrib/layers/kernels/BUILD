# Description:
#   Contains kernels for layers.

package(
    default_visibility = ["//tensorflow:__subpackages__"],
    licenses = ["notice"],  # Apache 2.0
)

exports_files(["LICENSE"])

cc_library(
    name = "sparse_feature_cross_kernel",
    srcs = ["sparse_feature_cross_kernel.cc"],
    deps = [
        "//tensorflow/core:framework_headers_lib",
        "//third_party/eigen3",
        "@farmhash_archive//:farmhash",
        "@protobuf_archive//:protobuf_headers",
    ],
    alwayslink = 1,
)
