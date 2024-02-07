SHELL :=/bin/bash

PHONY:all

all:
	mkdir -p build && \
	pushd build && \
	cmake .. && \
	cmake --build . && \
	popd && \
	pushd bin