## [main]

# Almost all CMake files should start with this
# You should always specify a range with the newest
# and oldest tested versions of CMake. This will ensure
# you pick up the best policies.
cmake_minimum_required(VERSION 3.1...3.23)

# This is your project statement. You should always list languages;
# Listing the version is nice here since it sets lots of useful variables
project(
  search-c
  VERSION 1.0
  LANGUAGES C
  )

add_subdirectory("search")
add_subdirectory("example")
