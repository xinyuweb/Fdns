cmake_minimum_required(VERSION 3.2)
project(Fdns)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    src/main.c
    README.MD)

add_executable(Fdns ${SOURCE_FILES} src/util.c src/util.h src/util.c)