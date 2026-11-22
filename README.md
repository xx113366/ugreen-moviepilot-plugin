# 绿联社区每日打卡 MoviePilot 插件库

这是一个 MoviePilot V3 第三方插件库，提供修改后的绿联社区签到插件。

## 添加方式

在 MoviePilot V3 的插件市场中选择“添加第三方仓库”，填写本仓库的 GitHub 地址，然后搜索并安装“绿联论坛签到”。

插件安装后，在配置中填写绿联社区 Cookie；也可以配置用户名和密码作为 Cookie 失效时的自动登录备用方式。

## 功能

- 自动访问绿联社区每日打卡页。
- 动态获取当前页面 `formhash` 并提交打卡。
- 已显示“今日已签到”时跳过重复提交。
- 提交后重新读取页面确认打卡结果。
- 记录连续签到天数、用户资料和积分变化。
- Cookie 失效时，可使用原插件的自动登录流程重试一次。

原始项目：<https://github.com/madrays/MoviePilot-Plugins>
原始插件：<https://github.com/madrays/MoviePilot-Plugins/blob/main/plugins.v3/ugreendiscuz/__init__.py>

本仓库保留原作者和项目出处，修改内容按 AGPL-3.0-only 许可发布。Cookie、密码等凭据只应填写在 MoviePilot 配置中，不要提交到仓库。
