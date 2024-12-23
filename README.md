# Webxdc Vite Template

[![npm package](https://img.shields.io/npm/v/@webxdc/create-vite-plugins.svg)](https://npmjs.com/package/@webxdc/create-vite-plugins)
[![CI](https://github.com/webxdc/create-vite-plugins/actions/workflows/ci.yml/badge.svg)](https://github.com/webxdc/create-vite-plugins/actions/workflows/ci.yml)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

Vite project template scaffolding for [Webxdc](https://webxdc.org) development.

## Scaffolding Your First Vite Project

With NPM:

```bash
$ npm create @webxdc/vite-plugins@latest
```

With PNPM:

```bash
$ pnpm create @webxdc/vite-plugins
```

With Yarn:

```bash
$ yarn create @webxdc/vite-plugins
```

Then follow the prompts!

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold a Webxdc + TypeScript project, run:

```bash
# npm 7+, extra double-dash is needed:
npm create @webxdc/vite-plugins@latest my-app -- --template vanilla-ts

# pnpm
pnpm create @webxdc/vite-plugins my-app --template vanilla-ts

# yarn
yarn create @webxdc/vite-plugins my-app --template vanilla-ts
```

Currently supported template presets include:

- `vanilla`
- `vanilla-ts`

You can use `.` for the project name to scaffold in the current directory.

## Credits

This project is based on [create-vite](https://github.com/vitejs/vite/tree/main/packages/create-vite).
