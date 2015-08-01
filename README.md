Hello World! with Creator (C++)
===============================

This is an example C++ project that can be built with [Creator][]. Do:

    ~/projects/hello_world_cpp $ creator
    creator: exporting to: build.ninja
    creator: running: ninja -f build.ninja
    [1/2] cl /nologo /c /FoC:\Users\niklas\Desktop\hello_....obj C:\Users\niklas\Desktop\hello_world\src\main.cpp
    main.cpp
    [2/2] cl /nologo /FeC:\Users\niklas\Desktop\hello_wor...:\Users\niklas\Desktop\hello_world\build\obj\main.obj

    ~/projects/hello_world_cpp $ creator run
    creator: running task 'hello_world:run'
    Hello, World!
