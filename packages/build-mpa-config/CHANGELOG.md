# Changelog

## 4.1.2

- [fix] format path in case of win32 system
- [fix] assign `routesFilePath` in `RaxGenerator`

## 4.1.1

- [feat] support frm mode

## 4.1.0

- [chore] remove `buildConfig.router` and add `enableRouter` to generator
- [fix] `renderComponent` -> `app.renderComponent`

## 4.0.5

- fix: `TabBar` resolve path
- chore: remove `x-if` in `TabBar`

## 4.0.4

- fix: every mpa page should redirect runApp file path

## 4.0.3

- feat: not render tabbar in frm container

## 4.0.2

- fix match rules for app.json

## 4.0.1

- feat add renderData of `isMPA`

## 4.0.0

- refactor: mpa runtime for each entry

## 3.2.7

- fix: tabBar window path wrong

## 3.2.6

- chore: change custom tab bar path to `src/components/CustomTabBar/index`

## 3.2.5

- feat add `props.pageConfig` in Rax App MPA page component

## 3.2.4

- fix: generate mpa entries when app.ts is entry in rax-app

## 3.2.3

- fix: generate mpa entries when app.ts is entry in ice.js framework

## 3.2.2

- fix: page wrapper `getInitialProps`

## 3.2.1

- chore: bump version

## 3.2.0

- [feat] support render custom tab bar in MPA
- [fix] the page doesn't render when the app.ts entry exports a component in mpa

## 3.1.1

- [chore] `hydrate` should be set when staticExport
