# Defaults

> Setting

The `wocss-settings-defaults` module contains your own project defaults variables, also variables and settings that are **required** for using any of the rest of the framework.

Install using npm:

```sh
$ npm install wocss-settings-defaults --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-settings-defaults';
```

### Variables list

#### Project colors

| Variable name | Default value |
|---------------|-------|
| $color-primary | `#7809BA` |
| $color-secondary | `#D4007C` |
| $color-tertiary | `#3A14BE` |

#### Project base

| Variable name | Default value |
|---------------|-------|
| $base-background-color | `#ffffff` |
| $base-font-family | `'Open Sans', 'Helvetica Neue Light', 'Helvetica Neue', 'Helvetica', 'Arial', sans-serif` |
| $base-font-size | `1em` |
| $base-font-weight | `400` |
| $base-line-height | `1.5 ` |
| $base-text-color | `#3d3d3d` |
| $base-border-color | `$color-primary` |
| $base-border-radius | `0.313em` |
| $base-border-width | `1px` |
| $base-border | `$base-border-width solid $base-border-color` |

#### Framework

| Variable name | Default value |
|---------------|-------|
| $base-spacing-unit | `1.5rem` |
