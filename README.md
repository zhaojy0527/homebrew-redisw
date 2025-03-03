# homebrew-redisw

这是 [redisw](https://github.com/zhaojy0527/redisw) 的 Homebrew Tap 仓库。redisw 是一个命令行下的 Redis 服务器连接管理工具，支持多服务器快速切换和查找的终端工具。

## 安装

```bash
brew tap zhaojy0527/redisw
brew install redisw
```

## 配置文件
安装完成后，redisw 会在用户目录下自动创建配置文件： ~/.config/redisw/redisw_config.yml 。
你可以在此文件中编辑配置你的 Redis 服务器信息。
编辑完成后重启 redisw 即可生效