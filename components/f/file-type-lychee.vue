<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(.54 1.9)scale(.96622)"><defs><linearGradient id="SVGhDbaeMzN"><stop offset="0" class="d9ofppbqf"/></linearGradient><linearGradient id="SVGZsURPbTz" x1="86.99" x2="152.52" y1="90.38" y2="90.38" gradientUnits="userSpaceOnUse" href="#SVGhDbaeMzN"/></defs><g transform="matrix(.3 0 0 .3 4.76 .55)"><path filter="blur(2.5px)" class="yxz2kwzyn"/><path class="ulm3qmbkz"/><path fill="url(#SVGZsURPbTz)" transform="translate(-51.66 -42.89)scale(.76517)" class="tgdnbmbvz"/><circle class="jlw2cbblp"/><circle class="fbaxrp9gz"/><path class="r2tdqf75q"/><path class="wrc15xaqz"/><path class="hwy14lb6y"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-lychee" /></template>
<style>
.d9ofppbqf {
  stop-color: var(--svg-color--d2d2d2, #d2d2d2);
}

.fbaxrp9gz {
  cx: 53.26px;
  cy: 26.44px;
  r: 2.24px;
  fill: var(--svg-color--676767, #676767);
}

.hwy14lb6y {
  fill: var(--svg-color--ffb7df, #ffb7df);
  d: path("m65.23 34.8l-.29.02q.06.87.09 1.76c-3.96 10-35.43 16.5-48.95 5.81A19 19 0 0 1 15 37.55l-.5.03c-11.77 11.8 34.32 24.33 52.24 1.5c.24-3.03.25-3.94-2.71-4.28");
}

.jlw2cbblp {
  cx: 33.86px;
  cy: 25.73px;
  r: 1.93px;
  fill: var(--svg-color--676767, #676767);
}

.r2tdqf75q {
  fill: none;
  stroke: var(--svg-color--676767, #676767);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-73px, 0.73px);
  d: path("M40.32 27.13c-.19 1.49.28 2.92 1.63 3.19c2.01.41 2.8-1 3.5-2.63");
}

.tgdnbmbvz {
  d: path("M152.52 103.86c-.77-22.84-14.5-41.68-32.42-41.74c-25.38-.08-37.7 33.2-31.56 49.34c17.67 13.97 58.79 5.47 63.98-7.6");
}

.ulm3qmbkz {
  fill: var(--svg-color--ff1999, #ff1999);
  d: path("M70.45 36.56c11.47.49 9.89 13.54 2.27 14.7c12.96 1.81 7 16.43 1.3 16.12c8.15 8.91.07 19.91-9.72 14.7c2.23 8.12-10.51 12.39-13.27 4.27c-4.53 13.58-16.81 8.56-16.73 2.23c-4.14 7.23-13.63 2.72-13.59-2.93c-7.25 4.14-16.32-4.67-11.24-11.38c-9.89-.24-9.65-12.44-2.25-14.17c1.72.7-.7 3.15-.02-.13c-10.24-3.31-8.53-14.4-1.3-14.3c-3.45-4.86 2.16-11.58 8.26-10.89");
}

.wrc15xaqz {
  fill: var(--svg-color--ff6fbf, #ff6fbf);
  d: path("M9.4 48.11c-6.18-.09-7.64 9.03 1.11 11.75l-.02.12c-6.29 1.45-6.47 11.45 1.96 11.64c-4.34 5.52 3.4 12.76 9.61 9.35c-.03 4.64 8.08 8.35 11.61 2.41c-.06 4.88 9.13 8.8 13.48.11c-4.15 1.55-8.7-1.13-8.66-4.24c-3.45 5.31-11.35 2-11.32-2.15c-6.05 3.05-13.59-3.43-9.37-8.36c-8.22-.18-8.04-9.11-1.91-10.41l.02-.1c-6.73-1.92-7.26-7.41-4.22-9.6zM52.42 77.6l-.08.21l.12-.12");
}

.yxz2kwzyn {
  d: path("M64.4 36.17c-.59-17.48-11.1-31.9-24.8-31.94C20.18 4.17 10.75 29.63 15.45 42c13.52 10.69 44.98 4.18 48.95-5.82");
  opacity: var(--svg-opacity--0-25, 0.25);
}

</style>
