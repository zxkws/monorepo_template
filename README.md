
## 前后端项目monorepo仓库模版
```bash

pnpm create vite packages/frontend --template react-ts

nest new packages/backend --skip-git --skip-install --package-manager pnpm


```
为子项目配置
```json
"extends": "../../tsconfig.json",
````

安装完依赖之后

```bash

pnpm start:backend

pnpm start:frontend

pnpm build:frontend

```
