load("@rules_cc//cc:defs.bzl", "cc_test")

cc_test(
    name = "hybrid_transceiver_test",
    size = "small",
    srcs = ["hybrid_transceiver_test.cc"],
    deps = [
        "//cyber:cyber_core",
        "//cyber/proto:unit_test_cc_proto",
        "@com_google_googletest//:gtest",
    ],
)

cc_test(
    name = "intra_transceiver_test",
    size = "small",
    srcs = ["intra_transceiver_test.cc"],
    deps = [
        "//cyber:cyber_core",
        "//cyber/proto:unit_test_cc_proto",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "rtps_transceiver_test",
    size = "small",
    srcs = ["rtps_transceiver_test.cc"],
    deps = [
        "//cyber:cyber_core",
        "//cyber/proto:unit_test_cc_proto",
        "@com_google_googletest//:gtest",
    ],
)

cc_test(
    name = "shm_transceiver_test",
    size = "small",
    srcs = ["shm_transceiver_test.cc"],
    deps = [
        "//cyber:cyber_core",
        "//cyber/proto:unit_test_cc_proto",
        "@com_google_googletest//:gtest",
    ],
)
