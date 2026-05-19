# 一、 概述

在 AI 发展迅猛的2026年，不管是**传统的前端工程师（Front-End-Engineer**）还是偏向**全栈的大前端（Big-Front-End-Engineer）**都已经在转变为  **AI 增强型全栈工程师-偏前端方向（AI-Enhanced Frontend Engineer）** ，核心工作转为与 AI 协作并进行代码质量把控。

所以2026年了前端的核心能力是什么？

**基础三件套** ：**HTML5** (语义化)、**CSS3** (Flex/Grid布局等)、 **JavaScript (ES6+)** 。Web 原生三件套，得真的吃透。html，css是页面的基础必须牢记，JS是前端交互的核心：事件循环、原型链、Promise 执行模型、ESM 模块化等重点知识必须深入掌握。其它比如浏览器渲染流程（DOM/CSSOM/布局/绘制/合成）、HTTP/2/3、安全防护（XSS/CSRF）等底层原理也需要理解。

**样式深入：**掌握基础的css之后学习更高效的样式声明方式。

* 预编译：scss、less预编译语言的学习。
* 原子化：UnoCSS 、Tailwind CSS(原子化CSS，开发效率极高)。

**TypeScript** ：2026年前端开发的**绝对标配** 。作为JS的超集，为JS添加类型检查，能显著减少bug，提升代码可维护性和工程化水平。

 **框架生态** (React、Vue  **都要会、**  **二选一深耕**) ：目前市场绝对主流的“元框架”开发模式，它们集成了路由、状态管理、渲染等能力，是项目的默认起点。

* **React 生态** ：大厂首选，生态最成熟。推荐学习**React + Next.js (全栈框架) + TypeScript**
* **Vue 生态** ：国内使用率极高，上手简单。推荐学习**Vue 3 + Nuxt 3 (全栈框架) + TypeScript**

**工程能力：从“会用脚手架”到“能看懂和调整工程栈”**

· 看懂项目的构建配置（Vite/Webpack/Rspack 任意一种）；

· 理解打包拆分、动态加载、CI/CD 流程；

· 能排查构建问题（路径解析、依赖冲突）。

**UI组件库** ：React生态推荐  **Ant Design / shadcn/ui** ；Vue生态推荐 **Element Plus / Naive UI**

**跨端和运行时：不只会“写 Web 页”**

·  **小程序**/**多端框架** （Taro、Uni-app）；

·  **混合方案** （RN/Flutter/WebView 通信机制）；

·  **桌面端** （Electron、Tauri）。

· 至少深耕一个“跨端主战场”（如 Web + 小程序 或 Web + Flutter）。

**全栈**/**后端能力：**

 **后端语言** ：**Node.js (NestJS框架)、python**

# 二、AI时代下的前端

**AI 时代的前端：不是写前端，也不是“写 AI”，而是“让 AI 真正跑进产品”**

·  **基础能力** ：调用 AI 平台 API（流式返回处理、增量渲染）；

·  **产品思维** ：哪些场景适合 AI（智能搜索、文档问答）；如何做权限控制、错误兜底。

框架红海：从“会用”到“用得值”：在选型时更关注：生态成熟度、框架在应用生命周期内的角色（渲染策略、数据流转、SEO、部署等）

工具上：现在有了ai的加入，开发方式也在变。所以你应该

· 能给 AI 写出清晰、可实现的需求描述（Prompt）；

· 能判断 AI 生成代码的质量、潜在风险、性能问题；

· 能基于生成结果做出合理抽象和重构。

业务上：不再是简单的“切图仔”画页面，而是“做体验+做增长”。不再是单一端，而是多平台多端开发。

·  **B 端产品** ：交互工程师 + 低代码拼装师 + 复杂表单处理专家；

·  **C 端产品** ：与产品运营深度捆绑，懂 A/B 测试、埋点、Funnel 分析、广告投放链路；

·  **跨平台** ：Web + 小程序 + App（RN/Flutter/WebView）混合形态成为常态。

## 2.1 AI通识学习

了解大模型基础（Transformer架构）、RAG原理ai相关的各种知识等。**系统学习提示工程** (Prompt Engineering)：学习如何编写高质量提示词，并重点掌握AI代码的结果评估与优化。

## 2.2 学习计划

#### **阶段二：框架进阶与AI工具应用 (2-3个月)**

 **选择并深入学习一个“元框架”** ，如 **React + Next.js + TypeScript** 。学有余力，可拓展Tailwind CSS。

 **实战：开发个人作品集网站** 。要求全程使用**TypeScript**，从零开始完成需求分析、编码、审查、测试直到部署。

#### **阶段三：AI能力深度应用与后端拓展 (2-3个月)**

 **AI API集成实战** ：

学习如何在前端调用OpenAI、百度文心一言等大模型API[](https://blog.csdn.net/m0_55049655/article/details/159893918)。

 **核心挑战** ：处理 **流式响应** （避免页面卡顿）、错误处理与降级方案[](https://blog.csdn.net/m0_55049655/article/details/159893918)。

 **实战** ：利用RAG技术构建一个本地知识库问答系统[](https://blog.csdn.net/m0_55049655/article/details/159893918)。

 **端侧**AI**探索** ：学习WebGPU加速技术，了解如何在浏览器中运行轻量级大模型。

 **拓展后端思维** ：学习Supabase等BaaS平台或Go/Node.js，培养全链路交付能力。

#### **阶段四：前沿技术与职业准备(持续进行)**

 **持续学习** ：关注前端技术动态，了解**WebAssembly**等新技术。

 **构建作品集** ：在GitHub个人主页上精心展示3-4个高质量项目。

## 2.3 前端提示词(Prompt）

提示词越具体，AI 越精准，好用的前端 Prompt，都离不开这 4 个核心要素：明确场景 + 技术栈 + 具体需求 + 输出要求

```md
举个反例：“帮我写个按钮组件”（模糊，AI 易瞎编）
举个正例：“用 Vue3 + TS + Tailwind CSS 写一个按钮组件，包含默认/禁用/高亮三种状态，hover 有过渡动画，带类型定义和注释，符合 ESLint 规范”（精准，AI 直接出可用代码）

基础组件类提示词：
用【Vue3/React】+【TS】+【Tailwind CSS/Element Plus/Ant Design】生成【组件名称，如：登录表单/商品卡片/分页组件】，要求：
1. 包含【具体功能，如：表单校验/分页切换/hover 动效】；
2. 支持【自定义属性，如：自定义颜色/尺寸/回调函数】；
3. 带完整 TS 类型定义、详细注释，符合 ESLint 规范；
4. 适配移动端响应式，兼容主流浏览器；
5. 输出完整可运行代码，复制就能直接导入项目。

用 Vue3 + TS + Element Plus 生成登录表单组件，要求：
1. 包含账号密码校验、记住密码、忘记密码功能；
2. 支持自定义提交按钮文本；
3. 带完整 TS 类型定义、详细注释，符合 ESLint 规范；
4. 适配移动端响应式，兼容主流浏览器；
5. 输出完整可运行代码，复制就能直接导入项目。

复杂组件封装提示词：
帮我封装一个【复杂组件名称，如：树形表格/弹窗表单/下拉搜索选择器】，技术栈【Vue3/React + TS】，要求：
1. 核心功能：【详细描述功能，如：树形表格支持勾选、展开/折叠、搜索筛选；弹窗表单支持表单联动、提交校验】；
2. 性能优化：【如：懒加载、防抖节流、避免重复渲染】；
3. 可扩展性：支持插槽、自定义事件、Props 传参，方便后续二次开发；
4. 附带使用示例、TS 类型说明、常见问题备注；
5. 代码结构清晰，分模块编写，便于维护。

报错快速修复提示词：
帮我分析以下前端报错和对应代码，要求：
1. 报错信息：【粘贴完整报错信息，如：Uncaught TypeError: Cannot read properties of undefined (reading 'value')】；
2. 对应代码：【粘贴报错相关的完整代码片段】；
3. 请找出报错根因，给出详细解释，然后提供完整的修复代码；
4. 补充优化建议，避免以后再出现类似问题；
5. 修复后的代码要符合项目技术栈【Vue3/React + TS】规范，可直接替换使用。


兼容性/Bug 排查提示词：
我遇到一个前端问题：【详细描述问题，如：iOS 微信浏览器样式错乱、页面滚动卡顿、接口请求跨域失败、组件渲染异常】；
项目技术栈：【Vue3/React + TS + 具体框架/工具】；
请帮我：
1. 分析可能的问题原因，列出所有可能性；
2. 给出每一种原因的解决方案和完整代码；
3. 提供预防措施，避免后续出现类似兼容性/性能问题；
4. 方案要简单易操作，不用复杂配置，直接能落地。


代码优化/重构提示词：
帮我重构以下前端代码，项目技术栈【Vue3/React + TS】，要求：
1. 原始代码：【粘贴需要重构的代码片段】；
2. 重构目标：优化代码结构、移除冗余代码、修复潜在 Bug、提升代码可读性和可维护性；
3. 保留原有的所有功能，不改变业务逻辑；
4. 加入 TS 类型定义（如果没有），补充必要注释，符合 ESLint 规范；
5. 给出重构前后的对比说明，解释优化的原因和好处。


版本升级迁移提示词：
帮我将【旧版本技术，如：Vue2 组件/Vue3 旧语法/jQuery 代码】迁移到【新版本技术，如：Vue3 组合式 API/TS/React 函数组件】，要求：
1. 原始代码：【粘贴需要迁移的代码片段/文件】；
2. 迁移要求：完全保留原业务功能，兼容原有项目配置，不引入新的依赖；
3. 遵循新版本的最佳实践，如：Vue3 组合式 API 规范、React Hooks 规范；
4. 补充迁移说明，列出需要注意的细节和可能出现的问题及解决方案；
5. 输出完整的迁移后代码，可直接替换使用。


样式快速生成/优化提示词：
帮我写/优化【元素/组件】的样式，技术栈【Tailwind CSS/CSS3/SCSS】，要求：
1. 样式需求：【详细描述，如：居中显示、圆角、阴影、hover 动效、响应式适配（375px/768px/1200px）、深色模式兼容】；
2. 样式规范：符合项目设计规范，避免样式冲突，代码简洁可复用；
3. 优化要求：减少冗余样式，提升样式加载速度，兼容主流浏览器；
4. 输出完整的样式代码，可直接复制到项目中使用，并给出使用说明。


交互效果实现提示词：
帮我实现【交互效果，如：下拉菜单动画、弹窗淡入淡出、滚动加载、拖拽排序、表单联动】，技术栈【Vue3/React + JS/TS】，要求：
1. 交互细节：【详细描述，如：弹窗点击遮罩关闭、下拉菜单hover展开、拖拽时显示提示、滚动加载到底部自动请求数据】；
2. 性能要求：避免卡顿、防抖节流处理，不影响页面其他功能；
3. 兼容性：适配移动端和PC端，兼容主流浏览器；
4. 输出完整的代码（HTML/CSS/JS/TS），复制就能用，附带使用说明和注意事项。


接口请求/类型生成提示词：
根据以下接口文档，生成【Vue3/React】项目的接口请求代码，要求：
1. 接口信息：【粘贴接口文档，包含请求地址、请求方式、参数、返回值】；
2. 技术栈：【Axios + TS】；
3. 输出内容：
   - 完整的接口请求函数封装（包含请求拦截、响应拦截、错误处理）；
   - 所有接口参数和返回值的 TS 类型定义；
   - Mock 数据生成（用于本地调试）；
   - 接口调用示例；
4. 代码符合项目规范，可直接导入项目使用。


测试用例/工程化配置提示词：
帮我生成【组件/函数】的测试用例，或【工程化配置文件】，要求：
1. 目标：【如：为登录组件写单元测试、生成 ESLint 配置、生成 Vitest 配置、生成 Dockerfile】；
2. 技术栈：【Vitest/Jest/ESLint/Docker】；
3. 具体要求：【如：测试用例覆盖渲染、交互、边界情况；配置文件适配 Vue3/React + TS 项目，包含常用配置】；
4. 输出完整的代码/配置文件，可直接复制到项目中使用，并给出配置说明和使用方法。


```

# 三、前端代码规范

## 3.1 命名规范

* **变量命名：** **❤️**

  * 使用小驼峰命名法：let userInfo = {}，const orderId = 123。
  * 尽量避免缩写而是使用完整的描述性命名，let buttonSubmit 比 btnSub 更清晰。
  * 布尔值应以 is, has, can, should 开头，如：isValid, hasError。
  * 常量使用全大写下划线分隔命名 (力求语义表达完整清楚， 不嫌名字长)：const API_ENDPOINT = ""。
  * 数组命名：名词+List, 名词+s, 如：userList
* **函数命名：** **❤️**

  * 使用动词短语或（动词 或者 动词+名词 形式）：getUserInfo(), fetchData(), validateForm()。saveShopCarData /openShopCarInfoDialog
  * 注：常用动词参考
    add / update / delete / detail / get
    附： 函数方法常用的动词:
    get 获取/set 设置,
    add 增加/remove 删除,
    create 创建/destory 销毁,
    start 启动/stop 停止,
    open 打开/close 关闭,
    read 读取/write 写入,
    load 载入/save 保存,
    begin 开始/end 结束,
    backup 备份/restore 恢复,
    import 导入/export 导出,
    split 分割/merge 合并,
    inject 注入/extract 提取,
    attach 附着/detach 脱离,
    bind 绑定/separate 分离,
    view 查看/browse 浏览,
    edit 编辑/modify 修改,
    select 选取/mark 标记,
    copy 复制/paste 粘贴,
    undo 撤销/redo 重做,
    insert 插入/delete 移除,
    add 加入/append 添加,
    clean 清理/clear 清除,
    index 索引/sort 排序,
    find 查找/search 搜索,
    increase 增加/decrease 减少,
    play 播放/pause 暂停,
    launch 启动/run 运行,
    compile 编译/execute 执行,
    debug 调试/trace 跟踪,
    observe 观察/listen 监听,
    build 构建/publish 发布,
    input 输入/output 输出,
    encode 编码/decode 解码,
    encrypt 加密/decrypt 解密,
    compress 压缩/decompress 解压缩,
    pack 打包/unpack 解包,
    parse 解析/emit 生成,
    connect 连接/disconnect 断开,
    send 发送/receive 接收,
    download 下载/upload 上传,
    refresh 刷新/synchronize 同步,
    update 更新/revert 复原,
    lock 锁定/unlock 解锁,
    check out 签出/check in 签入,
    submit 提交/commit 交付,
    push 推/pull 拉,
    expand 展开/collapse 折叠,
    enter 进入/exit 退出,
    abort 放弃/quit 离开,
    obsolete 废弃/depreciate 废旧,
    collect 收集/aggregate 聚集
* **组件命名：** **❤️**

  * Vue 和 React 组件名使用大驼峰命名法：UserProfile, OrderList。
* **文件命名：**  **❤️** （包括文件夹，JS、CSS、SCSS、HTML、PNG 文件命名）

  * 全部采用小写方式， 以中划线分隔：user-profile.vue，order-list.js。
  * 每个文件只包含一个组件或一个功能模块，避免混杂多个功能。
* **命名严谨性（可读性）** **❤️**

  * 代码中的命名严禁使用拼音与英文混合的方式，更不允许直接使用中文的方式。（除特殊含义命名：如shuidi,jingdong)
  * 杜绝完全不规范的缩写，避免望文不知义
* **避免魔法数字**

```js
// 魔法数字
if (state === 1 || state === 2) {
  // ...
} else if (state === 3) {
  // ...
}

// 魔法数字改用常量映射
const UNPUBLISHED = 1;
const PUBLISHED = 2;
const DELETED = 3;

if (state === UNPUBLISHED || state === PUBLISHED) {
  // ...
} else if (state === DELETED) {
  // ...
}

```

## 3.2 html 规范

**基本规范：**

* 缩进：缩进使用 2 个空格（一个 tab）；
* 分块注释：在每一个组件模块，加上一对 HTML 注释。
* 优先使用语义化标签：
* 引号：统一使用双引号(" ") 而不是单引号(’ ')

## 3.3 css 规范

**命名：** **❤️**

* 类名使用小写字母，以中划线分隔
* id 采用驼峰式命名
* scss中的变量、函数、混合、placeholder采用驼峰式命名
* ID和class的名称总是使用可以反应元素目的和用途的名称，或其他通用的名称，代替表象和晦涩难懂的名称。

**选择器** **：** **❤️**

* css 选择器中避免使用标签名。这是从结构、表现、行为分离的原则来看，应该尽量避免css中出现HTML标签，并且在css选择器中出现标签名会存在潜在的问题。
* 尽量使用缩写属性
* 省略 0 后面的单位
* 尽量避免使用 ID 选择器及全局标签选择器防止污染全局样式

```css

// 不推荐：后代选择器
.content .title {
  font-size: 2rem;
}

// 推荐: 使用直接子代选择器
.content > .title {
  font-size: 2rem;
}
// 不推荐:
border-top-style: none; 
font-family: palatino, georgia, serif; 
font-size: 100%; line-height: 1.6; 
padding-bottom: 2em; 
padding-left: 1em;
 padding-right: 1em; 
 padding-top: 0;

// 推荐:
border-top: 0; 
font: 100%/1.6 palatino, georgia, serif; 
padding: 0 1em 2em;

// 不推荐:
 div {
   padding-bottom: 0px; 
   margin: 0em;
 }

// 推荐:
div {
    padding-bottom: 0; 
    margin: 0; 
}

```

LESS 规范 ： ❤️

将公共 less 文件放置在 同一全局文件夹

* 顺序组织
* * 1、@import;
  * 2、变量声明;
  * 3、样式声明；
* 避免嵌套层级过多，不超过三层

## 3.4 取值规范❤️

* **默认值：**

  * 函数参数中为参数提供默认值：function fetchData(url = "/default-url") {}。
  * 避免直接使用 undefined，使用 null 或适当的默认值作为占位符。
* **对象解构：**

  * 使用对象解构来获取对象中的值：const { name, age } = user;
  * 函数多个传参使用对象传参，解构取值；
  * 使用空值合并操作符：const value = input ?? "default"。
  * 空函数判断

```js
// 行参封装成对象，对象函数内部解构（防止漏穿顺序错误导致的问题）
const getMyInfo = (options) => {
  const { name, age, gender, address, phone, email } = options;
  // ...
}

// 使用
getMyInfo(
  {
    name: '张三',
    age: 18,
    gender: '男',
    address: '北京',
    phone: '123456789',
    email: '123456789@qq.com'
  }
)

// 优化前
props.onChange && props.onChange(e)
// 支持ES11
props?.onChange?.(e)
// 不支持ES11的老项目
const NOOP = () => 8
const { onChange = NOOP } = props
onChange(e)  

```

## 3.5 错误捕获规范❤️

* **try-catch：**
  对于所有异步请求使用 try-catch 捕获错误，确保错误不会被忽略：
  JSON 解析
  DOM 操作
  正则表达式
  第三方库调用
  浏览器 API 错误捕获
* **Promise 错误处理：**
  确保处理所有 Promise 的 catch，不要忽略潜在错误：
* **全局错误处理：**
  在 Vue 和 React 中设置全局错误处理机制，以便捕获捕获组件树中框架级的错误。(结合监控捕获上传日志）

```js
  try {
  const response = await fetchData();
} catch (error) {
  console.error("Error fetching data:", error);
}
const jsonData = '{"name": "John", "age": 30}';

try {
  const user = JSON.parse(jsonData); // 正确的 JSON 解析
  console.log(user.name); // "John"
} catch (error) {
  console.error("Invalid JSON:", error); // 捕获 JSON 解析失败
}
try {
  const element = document.getElementById("non-existent-id");
  element.innerText = "Hello"; // 如果 element 为空，则会抛出异常
} catch (error) {
  console.error("Failed to manipulate DOM:", error);
}
const userInput = "(test";

try {
  const regex = new RegExp(userInput); // 捕获不正确的正则表达式
  const result = regex.test("test");
  console.log(result); // true or false
} catch (error) {
  console.error("Invalid regular expression:", error);
}
try {
  const result = thirdPartyLibrary.doSomething();
} catch (error) {
  console.error("Error in third-party library:", error);
  alert("操作失败，请稍后重试");
}
// 在用户拒绝授权或操作不当兼容性等问题
try {
  navigator.geolocation.getCurrentPosition((position) => {
    console.log(position.coords);
  });
} catch (error) {
  console.error("Geolocation error:", error);
}  

fetchData().then(response => {
  // success
}).catch(error => {
  console.error("Error:", error); // 记录promise异常日志
});
// 使用 Vue.config.errorHandler 全局捕获错误
Vue.config.errorHandler = function (err, vm, info) {
  console.error('Error in component: ', vm);
  console.error('Error info: ', info);
  console.error('Error message: ', err.message);
};
class ErrorBoundary extends React.Component {
 

  componentDidCatch(error, errorInfo) {
    // 可以在此处记录错误日志或进行其他处理
    console.error("Caught an error:", error, errorInfo);
  }

 
}

export default ErrorBoundary;



```

## 3.6 Vue 规范

编码基础参考官方风格指南
组件结构：
   组件名使用大驼峰命名，且 name 字段应与文件名保持一致。
   组件名应该始终是多个单词组成（大于等于 2），避免与 HTML 元素相冲突。如：KebabCase
   组件文件名为小写字母加中划线格式: my-component.vue
Prop 定义 ：
   避免直接修改 props，应通过 data 创建本地副本再修改。
   必须使用 camelCase 驼峰命名
   必须指定类型
   必须加上注释，表明其含义
   必须加上 required 或者 default，两者二选其一

生命周期函数：按顺序排列生命周期函数：created -> mounted -> updated -> destroyed。
样式规范：使用作用域样式
模板：避免使用内联样式、内联事件，模板应简洁明了
v-for必须绑定key, 不涉及删除添加的list可以使用:key="index" ❤️
vue2 组件的 data 必须是一个函数
如果组件特性元素较多，应该主动换行
v-show 与 v-if 选择:如果运行时，需要非常频繁地切换，使用 v-show ；如果在运行时，条件很少改变，使用 v-if。
vue2 script 标签内部结构顺序 components > props > data > computed > watch > filter > 钩子函数（钩子函数按其执行顺序） > methods

router 中的命名规范
   name 命名规范采用KebabCase命名规范且和component组件名保持一致（因为要保持keep-alive特性，keep-alive按照component的name进行缓存，所以两者必须高度保持一致）
   path、childrenPoints 命名规范采用kebab-case命名规范（尽量vue文件的目录结构保持一致，方便找到对应文件）；

注意：vue中尽量不要手动操作 DOM

尽量使用 vue 的数据驱动更新 DOM，尽量（不到万不得已）不要手动操作 DOM，包括：增删改 dom 元素、以及更改样式、添加事件等。

vue3 （推荐）推荐使用组合式API，在实现需求的时候，将每一个功能粒度细化，在每一个功能前后加上注释标注该功能的开始和结束，推荐使用的两种注释格式：

函数颗粒度太细，推荐按照以下几种函数名区分函数的功能
处理数据请求之类的函数， 可以用动词+形容词或者名词的形式，比如获取验证码可以叫getCode
   处理各种交互操作的函数，可以用on + 形容词或者名词（可选） + 动词 的形式，比如onLogin
   处理数据逻辑的函数， 可以使用形容词或者名词 + change的形式，比如processChange
   处理业务逻辑的函数，大部分以动词开头，比如create，init， update， delete，少部分以名词开头，比如ssrRender
   hooks函数，以use开头，比如useGetCode，useLogin

组件的script中js的结构化，推荐按照props，emits，ref， computed， watch，methods，events，生命周期函数的顺序排列js代码

对于比较复杂的功能，或者有多个页面ui不同但是功能相似的逻辑，推荐封装为hooks：

```js
 props: {
   // 用户级别，用于显示皇冠个数
   userLevel：{
      type: String,
      required: true
   }
}

<MyComponent foo="a" bar="b" baz="c"
  foo="a" bar="b" baz="c"
  foo="a" bar="b" baz="c"
  />

  // 反例：
  <MyComponent foo="a" bar="b" baz="c" foo="a" bar="b" baz="c" foo="a" bar="b" baz="c" baz="c"/>

{
    path: '/file',
    name: 'File',
    component: Main,
    meta: {
      title: '文件服务',
      icon: 'ios-cloud-upload'
    },
    children: [
      {
        path: '/file/file-list',
        name: 'FileList',
        component: () => import('@/views/file/file-list.vue')
      },
    ]
  }

1. region格式
// #region 功能描述
// code
// #endregion
2. start - end 格式
// 功能 - start
// code
// 功能 - end
// 一个hooks可能不能完全满足所有的功能，所以需要输入和输出，
// 对于输入，可以分为两种：
//  1. 整个功能多个函数需要的输入，可以放在hooks函数中，即作为useXXX()的参数
//  2. 整个功能中只有一个或者两个函数需要的输入，可以放在该函数中，即作为getCode()的参数
// 对于输出，也可以分为两种：
//  1. 函数可以作为完整的功能，所有的需求需要的这个函数都可以完整的hooks中实现，
//  2. 函数不可以作为完整的功能，可以只返回核心功能，或者通过回调函数处理其他逻辑
export function useVerifyCode() {
  const codeText = ref("获取验证码");

  const getCode = (phone) => {}

  const countDown = () => {}

  return {
    codeText,
    getCode
  }
}

```

## 3.7 React 规范

* **函数式组件优先** ：React 组件应优先使用函数组件，结合 React Hooks 管理状态。
* **for循环加 key索引** ：**❤️**
* **组件复用性** ：
* 保持组件职责单一，避免组件过大。提取复用逻辑为自定义 Hooks。
* **JSX 书写规范** ：
* JSX 代码中每个标签属性必须换行书写：

## 3.8 JavaScript 规范

* **ES6+ 特性** ：应优先使用 ES6+ 语法，如 const, let, 箭头函数, 模板字符串, 解构赋值，避免使用 var。
* **箭头函数** ：优先使用箭头函数，特别是在回调函数和事件处理程序中，避免 this 指向问题。
* **括号** ：
* **条件判断和循环最多三层**
* **慎用 console.log**

## 3.9 提交代码规范


* **小步提交：** 每次提交应专注于一个小的功能或修复，避免过大的提交。
* **规范的 commit 信息** ：**❤️**
* 每次提交详细说明提交内容： **【项目】项目端+页面+功能说明；（** 如：【水滴信用】水滴小程序 详情页 底部广告隐藏）
* **避免大规模合并** ：在提交之前，请确保与主分支进行 rebase，避免复杂的合并冲突。

## 3.10 注释规范


 **函数和复杂逻辑必须有注释** ：

* 使用 JSDoc 标准注释函数：

```js

 /**
 * 获取用户数据
 * @param {string} userId 用户ID
 * @returns {Object} 用户数据
 */
const getUserData = (userId) => { ... };

```


## 3.11 逻辑判断规范


* **避免使用双等号 ==** ：应始终使用严格等于 === 来进行比较。（避免隐式转换产生的异常）
* **条件判断简洁化** ：（永辉）
* 尽量避免使用复杂的嵌套条件语句，必要时使用**早返回**减少嵌套层次。或者叫：“异常逻辑前置，正常逻辑后置”
* **三元运算符** ：对于简单的条件判断可以使用三元运算符，但应避免嵌套三元运算符。
* **复杂判断逻辑抽离成单独函数**
* **分支逻辑优化**

```js
// if else
const statusMap = (status: string) => {
    if(status === 'success') return 'SuccessFully'
    else if (status === 'fail') return 'failed'
        else if (status === 'danger') return 'dangerous'
    else if (status === 'info') return 'information'
    else if (status === 'text') return 'texts'
    else return status
}


// 使用映射进行优化， 代替分支逻辑
const STATUS_MAP = {
    'success': 'Successfull',
    'fail': 'failed',
    'warn': 'warning',
    'danger': 'dangerous',
    'info': 'information',
    'text': 'texts'
}

return STATUS_MAP[status] ?? status
// 复杂判断逻辑
function checkGameStatus() {
  if (remaining === 0 ||
    (remaining === 1 && remainingPlayers === 1) ||
    remainingPlayers === 0) {
      quitGame()
  }
}

// 复杂判断逻辑抽离成单独函数，更方便阅读
function isGameOver() {
  return (
    remaining === 0 ||
    (remaining === 1 && remainingPlayers === 1) ||
    remainingPlayers === 0
  );
}

function checkGameStatus() {
  if (isGameOver()) {
    quitGame();
  }
}

if (isValid) {
    if(data){
        // 逻辑  
    }
}

if (!data) return;
if (!isValid) return;
// 逻辑 
// 判断逻辑不要嵌套太深
function checkStatus() {
  if (isLogin()) {
    if (isVip()) {
      if (isDoubleCheck()) {
        done();
      } else {
        throw new Error('不要重复点击');
      }
    } else {
      throw new Error('不是会员');
    }
  } else {
    throw new Error('未登录');
  }
}

// 将判断逻辑的异常逻辑提前，将正常逻辑后置
function checkStatus() {
  if (!isLogin()) {
    throw new Error('未登录');
  }

  if (!isVip()) {
    throw new Error('不是会员');
  }

  if (!isDoubleCheck()) {
    throw new Error('不要重复点击');
  }

  done();
}

```



## 3.12  自检工具


* **Lint 工具** ：项目必须配置 ESLint，确保代码风格统一并避免潜在的错误, 开发工具配置代码检测插件。
* **单元测试** ：比较复杂重要的逻辑模块，编写 Jest 或 Mocha 等工具的单元测试，确保主要逻辑和组件的稳定性。
* **AI工具自动codeReview** , ：codeGeex, 豆包插件，或者GPT代码段落codeReview(实测GPT效果更好）；还有一款专业的codeReview工具：CodeRabbit；


## 3.13 性能优化规范

* **图片优化：**

  * 图片资源使用合适的尺寸与格式：一般使用2倍ui图尺寸即可 **❤️**
  * 图片懒加载：确保非首屏图片采用懒加载，减少初始加载体积。
* **CSS 优化：**

  * 避免使用无效的 CSS 规则，减少层级过深的选择器。
* **节流与防抖：** 对于频繁触发的用户操作（如输入、滚动、点击），使用节流（throttle）和防抖（debounce）技术，避免性能瓶颈。
* **减少重绘与重排**

  * 尽量减少 DOM 操作和样式修改，缓存 DOM 元素减少查询，避免频繁触发重绘（repaint）或重排（reflow）。
  * 脱离文档流进行大量的dom操作：通过 display: none 先移出文档流

```js
const list = document.getElementById('list');
list.style.display = 'none';  // 先隐藏列表，避免多次重排

for (let i = 0; i < 100; i++) {
  const li = document.createElement('li');
  li.textContent = `Item ${i}`;
  list.appendChild(li);
}

list.style.display = '';  // 批量操作完成后再显示  

```



## 3.14 SEO规范


### PC端SEO规范

#### **pc页面跳转保持** `<a> `**链接结构**

* **规范说明：pc端大部分跳转使用js跳转不利于seo；**
* **场景1：直接跳转页面无跳转逻辑（无埋点，无条件判断，无动态参数）**
  * 使用a链接直接跳转，设置静态 `href`链接

**场景2：跳转页面有逻辑处理（有埋点，条件判断等）**

* 保持 `<a>`****链接结构：跳转标签使用a链接替换设置默认 `href`地址（`href` 只是用作备份，保证地址可正常访问，供搜索引擎使用）
* 使用 ` event.preventDefault()` 阻止a链接默认事件
* 在 `JavaScript` 中控制跳转逻辑和事件


```js
<-- 使用a链接直接跳转-->
<a href="https://example.com/new-page" 
   id="link-with-logic" 
   class="dynamic-link">
  跳转到新页面
</a>
<-- 标签使用a链接替换设置默认href地址 -->
<a href="https://example.com/new-page" 
   id="link-with-logic" 
   class="dynamic-link">
  跳转到新页面
</a>
// js中控制跳转逻辑和事件

const link = document.getElementById('link-with-logic');
  link.addEventListener('click', function (event) {
    event.preventDefault();  // 阻止a链接默认跳转
  
    // 1. 打点（统计点击行为）
    trackClickEvent('详情页入口点击');

     // 更新 href 地址
     const newHref = `https://example.com/new-page?param1=${dynamicParam1}`;

    // 2. 登录效验
    if (isLoggedIn()) {
      // 用户已登录，跳转到目标页面
      window.location.href = newHref;
    } else {
      // 用户未登录，跳转到登录页面
    }  
  
  });

```
