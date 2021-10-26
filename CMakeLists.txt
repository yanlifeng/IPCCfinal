cmake_minimum_required(VERSION 3.16)
project(IPCC2022)

set(CMAKE_CXX_STANDARD 14)

aux_source_directory(./src/ SRCS)
add_executable(IPCC2022 ${SRCS})