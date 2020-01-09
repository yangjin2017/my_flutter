## MUMU模拟器链接
adb connect localhost:7555

## MUMU模拟器启动闪退
日志：Connection closed before full header was received
https://github.com/flutter/flutter/issues/21988
修改高级设置的显卡渲染模式为兼容（openGl）