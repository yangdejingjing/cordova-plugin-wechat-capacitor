![version](https://img.shields.io/npm/v/cordova-plugin-wechat-capacitor/latest.svg)

Fork自(https://github.com/xu-li/cordova-plugin-wechat)

## Ionic6 配置指南
修改capacitor.config.ts,添加如下代码
```
{
    cordova: {
        preferences: {
            WECHATAPPID: '你的APPID',
            UNIVERSALLINK: '你的UNIVERSALLINK'
        },
        staticPlugins: ['cordova-plugin-wechat-capacitor']
    }
}
```

