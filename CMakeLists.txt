cmake_minimum_required(VERSION 3.0)

set(PROJECT_NAME demo)

project(${PROJECT_NAME} VERSION 1.0.0 LANGUAGES C)

add_executable(${PROJECT_NAME} src/main.c)
