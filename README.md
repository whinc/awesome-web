# awesome-any
记录我使用过并且觉得好用的包，随着更新换代，此清单也会随之更新。


## Web

|类型| 精选库 |
|----|---------|
|网络请求|[axios](https://github.com/axios/axios)|
|UI库|[Bootstrap](https://github.com/twbs/bootstrap) \| [Bulma](https://github.com/jgthms/bulma) |
|图标|[Font Awesome](https://fontawesome.com/) \| [Iconfont](https://www.iconfont.cn/)|
|字体|[typography.js](https://github.com/KyleAMathews/typography.js)|
|表单校验|[async-validator](https://github.com/yiminghe/async-validator)|
|图表|[echarts](https://github.com/apache/incubator-echarts) \| [AntV](https://github.com/antvis) |
|代码编辑器|[monaco-editor](https://github.com/microsoft/monaco-editor)|
|语法高亮|[prism](https://github.com/PrismJS/prism) \| [highlight.js](https://github.com/highlightjs/highlight.js) |
|堆栈处理|[stacktrace.js](https://github.com/stacktracejs/stacktrace.js)|
|终端|[xterm.js](https://github.com/xtermjs/xterm.js)|
|截图|[html2canvas](https://github.com/niklasvh/html2canvas)
|excel解析|[sheetjs](https://github.com/SheetJS/sheetjs)|
|水印|[web-watermark](https://github.com/hjyker/web-watermark)|

  
## [React](https://github.com/facebook/react/)
A declarative, efficient, and flexible JavaScript library for building user interfaces https://zh-hans.reactjs.org

**框架**
- [next.js](https://github.com/zeit/next.js) The React Framework https://nextjs.org
- [gatsby](https://github.com/gatsbyjs/gatsby) Build blazing fast, modern apps and websites with React https://www.gatsbyjs.org

**脚手架**
- [create-react-app](https://github.com/facebook/create-react-app) Set up a modern web app by running one command. https://facebook.github.io/create-react-app/
  - [customize-cra](https://github.com/arackaf/customize-cra) Override webpack configurations for create-react-app 2.0
  - [workerize-loader](https://github.com/developit/workerize-loader) Automatically move a module into a Web Worker（支持CRA）
- [create-react-library](https://github.com/transitive-bullshit/create-react-library) CLI for creating reusable react libraries.
- [parcel](https://github.com/parcel-bundler/parcel) Blazing fast, zero configuration web application bundler https://parceljs.org
- [tsdx](https://github.com/palmerhq/tsdx) Zero-config CLI for TypeScript package development

**CSS-in-JS**
- [jss](https://github.com/cssinjs/jss) JSS is an authoring tool for CSS which uses JavaScript as a host language. https://cssinjs.org
- [emotion](https://github.com/emotion-js/emotion) CSS-in-JS library designed for high performance style composition https://emotion.sh/
- [styled-components](https://github.com/styled-components/styled-components) Use the best bits of ES6 and CSS to style your apps without stress https://styled-components.com
- [polished](https://github.com/styled-components/polished) A lightweight toolset for writing styles in JavaScript  https://polished.js.org/
- [clsx](https://github.com/lukeed/clsx) A tiny utility for constructing `className` strings conditionally.

**组件库**
- [ant-design](https://github.com/ant-design/ant-design) A UI Design Language and React UI library https://ant.design
  - [pro-components](https://github.com/ant-design/pro-components) 基于 antd 封装的抽象度更高的组件
  - [react-component](https://github.com/react-component) antd 组件仓库的集合，要阅读 antd 组件源码时来这里。
  - [ant-design-colors](https://github.com/ant-design/ant-design-colors) Color Palettes Calculator of Ant Design https://ant.design/docs/spec/colors
  - [ant-design-icons](https://github.com/ant-design/ant-design-icons) Ant Design SVG Icons https://ant.design/components/icon/
- [material-ui](https://github.com/mui-org/material-ui) React components that implement [Google's Material Design](https://www.google.com/design/spec/material-design/introduction.html). https://material-ui.com/
  - [@material-ui/system](https://material-ui.com/system/basics/) provides low-level utility functions called "style functions" for building powerful design systems

**路由**
- [react-router](https://github.com/ReactTraining/react-router) Declarative routing for React https://reacttraining.com/react-router/

**状态管理**
- [redux](https://github.com/reduxjs/redux) Predictable state container for JavaScript apps http://redux.js.org
  - [react-redux](https://github.com/reduxjs/react-redux) Official React bindings for Redux https://react-redux.js.org
  - [reselect](https://github.com/reduxjs/reselect) Selector library for Redux
  - [redux-toolkit](https://github.com/reduxjs/redux-toolkit) The official, opinionated, batteries-included toolset for efficient Redux development https://redux-toolkit.js.org
  - [rematch](https://github.com/rematch/rematch) A Redux Framework https://rematch.github.io/rematch/
  - [dva](https://github.com/dvajs/dva) React and redux based, lightweight and elm-style framework. https://dvajs.com/
  - [redux-devtools-extension](https://github.com/zalmoxisus/redux-devtools-extension) Redux DevTools extension. http://extension.remotedev.io
- [mobx](https://github.com/mobxjs/mobx) Simple, scalable state management. http://mobx.js.org
  - [mobx-react](https://github.com/mobxjs/mobx-react) React bindings for MobX
  - [mobx-react-lite](https://github.com/mobxjs/mobx-react-lite)  Lightweight React bindings for MobX based on React 16.8 and Hooks https://mobx-react.js.org
  - [mobx-state-tree](https://github.com/mobxjs/mobx-state-tree) Opinionated, transactional, MobX powered state container combining the best features of the immutable and mutable world for an optimal DX https://mobx-state-tree.js.org/

|类型| Github |
|----|---------|
|不可变数据|[immer](https://github.com/immerjs/immer)|
|Hooks|[react-use](https://github.com/streamich/react-use) \| [ahooks](https://github.com/alibaba/hooks) \| [use-immer](https://github.com/immerjs/use-immer) |

**精选组件**

与 [antd-社区精选组件](https://ant.design/docs/react/recommendation-cn) 互补。

|类型| 精选组件 |
|----|---------|
|富文本编辑器|[draft-js](https://github.com/facebook/draft-js) \| [slate](https://github.com/ianstormtaylor/slate)|
|新手引导|[reactour](https://github.com/elrumordelaluz/reactour)|
|滚动条|[react-custom-scrollbars](https://github.com/malte-wessel/react-custom-scrollbars)|
|AutoSizer|[react-virtualized-auto-sizer](https://github.com/bvaughn/react-virtualized-auto-sizer)|
|Excel表格|[react-data-grid](https://github.com/adazzle/react-data-grid) \| [react-handsontable](https://github.com/handsontable/react-handsontable)|
|图表|[echarts-for-react](https://github.com/hustcc/echarts-for-react) \| [ant-design-charts](https://github.com/ant-design/ant-design-charts) |
|图编辑器|[x6](https://github.com/antvis/x6)|

**参考**
- [awesome-react-hooks](https://github.com/rehooks/awesome-react-hooks)
- [awesome-react](https://github.com/enaqx/awesome-react)
- [awesome-react-components](https://github.com/brillout/awesome-react-components)

<details><summary>Frontend Engineering</summary><p>
  
## Frontend Engineering

**打包器**
- [gulp](https://github.com/gulpjs/gulp) The streaming build system https://www.gulpjs.com.cn/
- [webpack](https://github.com/webpack/webpack) A bundler for javascript and friends. https://webpack.js.org
- [rollup](https://github.com/rollup/rollup) Next-generation ES module bundler https://rollupjs.org
- [parcel](https://github.com/parcel-bundler/parcel) Blazing fast, zero configuration web application bundler https://parceljs.org

**预处理器**
- [babel](https://github.com/babel/babel)  Babel is a compiler for writing next generation JavaScript. https://babeljs.io/
  - [babel-plugin-macros](https://github.com/kentcdodds/babel-plugin-macros) Allows you to build simple compile-time libraries 
    - [awesome-babel-macros](https://github.com/jgierer12/awesome-babel-macros)
- [sass](https://github.com/sass/sass) Sass makes CSS fun! https://sass-lang.com
- [pug](https://github.com/pugjs/pug) robust, elegant, feature rich template engine. https://pugjs.org

**代码质量**
- [prettier](https://github.com/prettier/prettier) Prettier is an opinionated code formatter. https://prettier.io
- [eslint](https://github.com/eslint/eslint) A fully pluggable tool for identifying and reporting on patterns in JavaScript https://eslint.org
- [stylelint](https://github.com/stylelint/stylelint) A mighty, modern style linter https://stylelint.io/
 
**测试框架**
- [testing-library](https://github.com/testing-library) Simple and complete testing utilities that encourage good testing practices https://testing-library.com/
- [react-hooks-testing-library](https://github.com/testing-library/react-hooks-testing-library) Simple and complete React hooks testing utilities that encourage good testing practices. https://react-hooks-testing-library.com
- [jest](https://github.com/facebook/jest) Delightful JavaScript Testing. https://jestjs.io
- [storybook](https://github.com/storybookjs/storybook) UI component dev & test: React, Vue, Angular, React Native, Ember, Web Components & more! https://storybook.js.org 

**API文档**
- [tsdoc](https://github.com/microsoft/tsdoc) A doc comment standard for the TypeScript language https://microsoft.github.io/tsdoc/
- [jsdoc](https://github.com/jsdoc/jsdoc) An API documentation generator for JavaScript. https://jsdoc.app/ 
- [typedoc](https://github.com/TypeStrong/TypeDoc) Documentation generator for TypeScript projects. https://typedoc.org 

**文档网站**
- [docusaurus](https://github.com/facebook/docusaurus) Easy to maintain open source documentation websites. https://docusaurus.io 

**发布**
- [standard-version](https://github.com/conventional-changelog/standard-version) Automate versioning and CHANGELOG generation, with semver.org and conventionalcommits.org
- [semantic-release](https://github.com/semantic-release/semantic-release): Fully automated version management and package publishing https://semantic-release.gitbook.io
>参考：[约定式提交规范](https://www.conventionalcommits.org/zh-hans)

**部署**
- [now](https://github.com/zeit/now) The easiest way to deploy websites https://zeit.co

**Git 提交**
- [husky](https://github.com/typicode/husky)  Git hooks made easy
- [lint-staged](https://github.com/okonet/lint-staged) Run linters on git staged files
- [cz-cli](https://github.com/commitizen/cz-cli) The commitizen command line utility

**其他工具**
- [browserslist](https://github.com/browserslist/browserslist) Share target browsers between different front-end tools, like Autoprefixer, Stylelint and babel-preset-env https://twitter.com/browserslist

</p></details>

<details><summary>Node.js</summary><p>
  
## [Node.js](https://github.com/nodejs/node)

Node.js JavaScript runtime. https://nodejs.org/ ([中文](http://nodejs.cn/))

**脚手架**
- [tsdx](https://github.com/palmerhq/tsdx) Zero-config CLI for TypeScript package development
- [oclif](https://github.com/oclif/oclif) Node.js Open CLI Framework. https://oclif.io

**开发工具**
- [nvm](https://github.com/creationix/nvm) Node Version Manager - Simple bash script to manage multiple active node.js versions
- [nodemon](https://github.com/remy/nodemon) Monitor for any changes in your node.js application and automatically restart the server - perfect for development http://nodemon.io/ 
- [ts-node](https://github.com/TypeStrong/ts-node) TypeScript execution and REPL for node.js 

**Web 框架**
- [koa](https://github.com/koajs/koa) Expressive middleware for node.js using ES2017 async functions https://koajs.com
- [express](https://github.com/expressjs/express/) Fast, unopinionated, minimalist web framework for node. https://expressjs.com
- [egg](https://github.com/eggjs/egg) Born to build better enterprise frameworks and apps with Node.js & Koa https://eggjs.org/zh-cn/

**基础库**
- [lodash](https://github.com/lodash/lodash/) A modern JavaScript utility library delivering modularity, performance, & extras. https://lodash.com/
- [dayjs](https://github.com/iamkun/dayjs) Day.js 2KB immutable date library alternative to Moment.js with the same modern API 
- [date-fns](https://github.com/date-fns/date-fns) Modern JavaScript date utility library  https://date-fns.org
- [minimatch](https://github.com/isaacs/minimatch) a glob matcher in javascript
- [node-glob](https://github.com/isaacs/node-glob) Match files using the patterns the shell uses, like stars and stuff.
- [dotenv](https://github.com/motdotla/dotenv) Loads environment variables from .env for nodejs projects. 
- [dotenv-expand](https://github.com/motdotla/dotenv-expand) Variable expansion for dotenv. Expand variables already on your machine for use in your .env file.
- [log4js-node](https://github.com/log4js-node/log4js-node) A port of log4js to node.js

**浏览器**
- [jsdom](https://github.com/jsdom/jsdom) A JavaScript implementation of the WHATWG DOM and HTML standards, for use with node.js
- [puppeteer](https://github.com/GoogleChrome/puppeteer) Headless Chrome Node API https://pptr.dev 

**Git**
- [nodegit](https://github.com/nodegit/nodegit) Native Node bindings to Git. https://www.nodegit.org/
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) A pure JavaScript implementation of git for node and browsers! https://isomorphic-git.org/ (node & browser)

**编译器**
- [antlr4](https://github.com/antlr/antlr4) ANTLR (ANother Tool for Language Recognition) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. http://antlr.org 
- [antlr4ts](https://github.com/tunnelvisionlabs/antlr4ts) Optimized TypeScript target for ANTLR 4 
- [pegjs](https://github.com/pegjs/pegjs) PEG.js: Parser generator for JavaScript https://pegjs.org/ 


**其他**
- [shelljs](https://github.com/shelljs/shelljs) Portable Unix shell commands for Node.js https://documentup.com/shelljs/shelljs
- [flexsearch](https://github.com/nextapps-de/flexsearch/) Next-Generation full text search library for Browser and Node.js (node & browser)
- [json-server](https://github.com/typicode/json-server) Get a full fake REST API with zero coding in less than 30 seconds

</p></details>

  
<details><summary>Specifications</summary><p>

  
## Specifications


**标准规范**

- [HTML5](https://html.spec.whatwg.org/multipage/)
- [ecma262](https://github.com/tc39/ecma262) Status, process, and documents for ECMA-262 https://tc39.es/ecma262/
- [estree](https://github.com/estree/estree) The ESTree Spec
- [JSON](http://json.org/json-zh.html) (JavaScript Object Notation) is a lightweight data-interchange format.
- [JSON-RPC 2.0 Specification](https://www.jsonrpc.org/specification) JSON-RPC is a stateless, light-weight remote procedure call (RPC) protocol （[中文版](http://wiki.geekdream.com/Specification/json-rpc_2.0.html)）
- [language-server-protocol](https://github.com/microsoft/language-server-protocol) Defines a common protocol for language servers. https://microsoft.github.io/language-server-protocol/
- [DWARF Debugging Standard](http://dwarfstd.org/) DWARF is a debugging file format used by many compilers and debuggers to support source level debugging.
- [WebAssembly](https://webassembly.org/) (abbreviated Wasm) is a binary instruction format for a stack-based virtual machine.

</p></details>
  
<details><summary>Others</summary><p>
  
## Others

- [province-city-china](https://github.com/uiwjs/province-city-china) 中国最全最新中国【省、市、区县、乡镇街道】json,csv,sql数据

**Browser Extensions**

- [HeaderEditor](https://github.com/FirefoxBar/HeaderEditor) Manage browser's requests, include modify the request headers and response headers, redirect requests, cancel requests https://he.firefoxcn.net/

**软件**
- [Visual Studio Code](https://code.visualstudio.com/): https://code.visualstudio.com
- [source-code-pro](https://github.com/adobe-fonts/source-code-pro): Monospaced font family for user interface and coding environments


</p></details>

## References
* [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs#command-line-utilities)
* [Open Source Awards](https://osawards.com/)
* [awesome-cheatsheets](https://github.com/skywind3000/awesome-cheatsheets)

