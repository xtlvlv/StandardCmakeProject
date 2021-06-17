# 介绍

- cpp项目的标准目录组成，空项目

# 目录层次介绍

## bin
- 二进制文件

## build
- 构建中的中间文件夹

## cmake
- cmake函数文件夹

## lib
- 库的输出路径

## src 
- 源码路径

## tests
- 测试代码路径

## CmakeLists.txt

- cmake文件，进入bulid目录执行 `cmake ..`
- `cmake dir` dir是 `CmakeLists.txt` 文件所在路径
- 会自动生成makefile文件
```bash
    cmake ..
    make
```

## Makefile

- makefile文件，用cmake的话可以不用这个