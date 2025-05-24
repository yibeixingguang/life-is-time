📘 Time is Life - 珍惜生命的每一刻
Time is Life 是一个帮助用户意识并珍惜时间的应用程序，通过展示生命倒计时、管理时间目标和记录时间日志，让用户更好地理解时间的珍贵性。

🚀 特性
生命倒计时主视图

线性进度条显示
环形图表显示
数字计时器（年/月/日/时/分/秒）
自定义时间目标

创建带有截止日期的时间目标
支持分类和描述
多种提醒频率选项
时间日志记录

记录每日感想和反思
情绪跟踪（好/一般/不好）
标签分类和筛选
🛠️ 技术栈
前端: React 18, Next.js (App Router), Tailwind CSS, Shadcn UI, Framer Motion
前端: React 18, Next.js（App Router），Tailwind CSS，Shadcn UI，Framer Motion
状态管理: Zustand
数据存储: 本地存储 (localStorage)
🏗️ 项目结构
src/
├── app/                # Next.js App Router 页面
│   ├── goals/          # 时间目标页面
│   ├── logs/           # 时间日志页面
│   ├── settings/       # 设置页面
│   ├── layout.tsx      # 根布局
│   └── page.tsx        # 首页（生命倒计时）
├── components/         # React 组件
│   ├── layout/         # 布局组件（导航栏等）
│   ├── life-countdown/ # 生命倒计时相关组件
│   ├── time-goals/     # 时间目标相关组件
│   ├── time-logs/      # 时间日志相关组件
│   ├── user-settings/  # 用户设置组件
│   └── ui/             # UI 基础组件
├── lib/                # 工具函数
├── store/              # Zustand 状态管理
└── styles/             # 全局样式
📋 未来功能
轻量社交广场 - 匿名分享时间感悟
时间资产账户 - 记录时间投资方向
AI 情绪分析 - 自动分析日志情绪
导出/导入数据功能
🚦 快速开始
克隆仓库

git clone https://github.com/yourusername/time-is-life.git
cd time-is-life
安装依赖

npm install
启动开发服务器

npm run dev
构建生产版本

npm run build
📝 许可证
MIT  麻省理工学院
