---
title: Flutter Hello World
tags: [flutter, dart, hello world] 
categories: [flutter]
date: 2020-05-17 13:40:00
---
## Flutter是什么
[Flutter](https://github.com/flutter/flutter) is Google's SDK for crafting beautiful, fast user experiences for mobile, web and desktop from a single codebase. Flutter works with existing code, is used by developers and organizations around the world, and is free and open source.
Flutter是基于Dart语言的.
## Dart Hello World
[Dart](https://github.com/dart-lang/sdk)是什么
A client-optimized language for fast apps on any platform.
打卡在线[DartPad](https://dartpad.dev)，简单hello world如下
``` dart
void main() {
  print('Hello World');
}
```
## Flutter Hello World
打开Android Studio，安装Dart和Flutter插件;选择Flutter Examples目录下的Hello World.
### 项目结构如下
```
├── hello_world
    │   ├── android
    │   │   └── ...
    │   ├── fuchsia
    │   │   └── meta
    │   │       ├── hello_world.cmx
    │   ├── ios
    │   │   ├── ...
    │   ├── lib
    │   │   └── arabic.dart
    │   │   └── main.dart
    │   ├── test
    │   │   ├── hell_test.dart
    │   ├── web
    │   │   ├── index.html
    ├── pubspec.lock
    └── pubspec.yaml
    ├── README.md
```
正如Flutter的定义一样Flutter代码能生存到移动端```android ios fuchsia```,web端.
### 代码启动入口```main.dart```
``` dart
// Copyright 2015 The Chromium Authors. All rights reserved.  
// Use of this source code is governed by a BSD-style license that can be  
// found in the LICENSE file.  
  
import 'package:flutter/widgets.dart';  
  
void main() => runApp(const Center(child: Text('Hello, world!', textDirection: TextDirection.ltr)));
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA3ODA1NTc2NSw4MjQ4MjIzMTIsMTg3MT
A4ODM4NCwtMTI0NjI4MDgxOCw4MDcyNzg3NjMsLTM2NjI0MzQ3
MCwtMzM1OTkwMzk2XX0=
-->