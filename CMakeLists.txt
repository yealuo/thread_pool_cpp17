cmake_minimum_required(VERSION 3.28)
project(thread_pool)

set(CMAKE_CXX_STANDARD 17)

add_executable(thread_pool main_test.cpp
        thread_pool.h
        thread_pool.cpp)
