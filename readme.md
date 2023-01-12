## 这是一个卖不上钱的项目

### 目录结构

```
├── .husky                                   // git hook 配置文件
├── __mock__                                 // mock数据文件
├── public                                   // 公共文件目录（打包时并不需要打进去）
├── dist                                     // 打包目录
├── locales                                  // 国际化配置
├── src                                      // 业务代码模块
│   ├── assets                               // 公共静态文件
│   ├── components                           // 自定义业务组件
│   ├── config                               // 配置文件 （router.config env.config
│   ├── screens                              // 业务模块
│   ├── public                               // 非打包文件目录
│   ├── services                             // api服务
│   ├── models                               // 状态管理
│   ├── utils                                // 工具文件
│   ├── app.js                               // 根组件
│   └── index.js                             // 入口文件
├── webpack                                  // 项目构建/启动 配置
├── tsconfig.json                            // ts配置文件
├── package.json                             // 依赖管理文件
├── package-lock.json                        // 依赖版本管理文件
└── README.md                                // overview
```
