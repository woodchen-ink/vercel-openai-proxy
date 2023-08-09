# vercel-reverse-proxy

本项目是vercel反向代理，用于代理OPENAI

Telegram交流群：https://t.me/ai_cn2023

## 部署
[![Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/woodchen-ink/vercel-openai-proxy)


## 使用方法
1 部署。部署有两种方法，一是直接点击上方按钮一键部署，二是可以先fork本项目，再登录[vercel](https://vercel.com/)网站新建
![新建项目](img/newproject.png)

2 绑定自己的域名(不是必须，使用vercel自带的子域名也可以，但是自带的域名vercel.app在国内网络环境不好的情况下不可用)  
绑定域名时按照vercel上的说明配置即可，其实就是在你的域名上配了一个子域名，cname到vercel服务器

3 访问 域名/ 
映射规则为根目录

## 示例
例1 访问https://example.com/v1/chat/completions 
实际上会替换为https://api.openai.com/v1/chat/completions
