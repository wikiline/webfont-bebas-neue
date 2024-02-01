# WebFont Bebas Neue

Package for integrating `Bebas Neue` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@wikiline/webfont-bebas-neue?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@wikiline/webfont-bebas-neue?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@wikiline/webfont-bebas-neue?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @wikiline/webfont-bebas-neue
```

## Usage (CSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```css
body {
  font-family: 'Bebas Neue', sans-serif;
}
```

### Importing

```css
@import "~@wikiline/webfont-bebas-neue/src/css/all.css";
@import "~@wikiline/webfont-bebas-neue/src/css/all-normal.css";
```

To import specific fonts, you can use:

```css
@import "~@wikiline/webfont-bebas-neue/src/css/weight-100.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-100-normal.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-200.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-200-normal.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-300.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-300-normal.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-400.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-400-normal.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-500.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-500-normal.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-700.css";
@import "~@wikiline/webfont-bebas-neue/src/css/weight-700-normal.css";
```

Note: Also, each file is presented in a minimized form.

### Variables

Each font uses the following CSS variables to set the font display property with the default `swap` value if CSS
variables are not defined:

```css
:root {
  --font-display: swap;
  --font-display-bebas-neue: swap;
}
```

## Usage (LESS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```less
body {
  font-family: 'Bebas Neue', sans-serif;
}
```

### Importing

```less
@import "~@wikiline/webfont-bebas-neue/src/less/all";
@import "~@wikiline/webfont-bebas-neue/src/less/all-normal";
```

To import specific fonts, you can use:

```less
@import "~@wikiline/webfont-bebas-neue/src/less/weight-100";
@import "~@wikiline/webfont-bebas-neue/src/less/weight-100-normal";
@import "~@wikiline/webfont-bebas-neue/src/less/weight-200";
@import "~@wikiline/webfont-bebas-neue/src/less/weight-200-normal";
@import "~@wikiline/webfont-bebas-neue/src/less/weight-300";
@import "~@wikiline/webfont-bebas-neue/src/less/weight-300-normal";
@import "~@wikiline/webfont-bebas-neue/src/less/weight-400";
@import "~@wikiline/webfont-bebas-neue/src/less/weight-400-normal";
@import "~@wikiline/webfont-bebas-neue/src/less/weight-700";
@import "~@wikiline/webfont-bebas-neue/src/less/weight-700-normal";
```

### Variables

Each font uses the following LESS variables to set the font display property with the default `swap` value if SCSS
variables are not defined:

```less
@font-display: swap;
@font-display-bebas-neue: swap;
```

You can declare these variables globally or import them from a file: `_variables.less`.

```less
@import "~@wikiline/webfont-bebas-neue/src/less/config/_variables";
```

## Usage (SCSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```scss
body {
  font-family: 'Bebas Neue', sans-serif;
}
```

### Importing

```scss
@import "~@wikiline/webfont-bebas-neue/src/scss/all";
@import "~@wikiline/webfont-bebas-neue/src/scss/all-normal";
```

To import specific fonts, you can use:

```scss
@import "~@wikiline/webfont-bebas-neue/src/scss/weight-100";
@import "~@wikiline/webfont-bebas-neue/src/scss/weight-100-normal";
@import "~@wikiline/webfont-bebas-neue/src/scss/weight-200";
@import "~@wikiline/webfont-bebas-neue/src/scss/weight-200-normal";
@import "~@wikiline/webfont-bebas-neue/src/scss/weight-300";
@import "~@wikiline/webfont-bebas-neue/src/scss/weight-300-normal";
@import "~@wikiline/webfont-bebas-neue/src/scss/weight-400";
@import "~@wikiline/webfont-bebas-neue/src/scss/weight-400-normal";
@import "~@wikiline/webfont-bebas-neue/src/scss/weight-700";
@import "~@wikiline/webfont-bebas-neue/src/scss/weight-700-normal";
```

### Variables

Each font uses the following SCSS variables to set the font display property with the default `swap` value if SCSS
variables are not defined:

```scss
$font-display: swap;
$font-display-bebas-neue: swap;
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the SIL
Open Font License, v1.1. Some fonts use the Apache 2 license. The Ubuntu fonts use the Ubuntu Font License v1.0.
