<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(.22 .16)scale(.96206)"><defs><linearGradient id="SVGHFEUkd6S"><stop offset="0" class="l1q-mxfjf"/><stop offset="1" class="oi4kq9b7z"/></linearGradient></defs><path fill="url(#SVGHFEUkd6S)" transform="translate(2.76 1.99)scale(.11923)" class="qvdjvbboh"/><path class="oq05-nbzl"/><path class="d9wmqpb7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ng-routing-js2" /></template>
<style>
.d9wmqpb7v {
  fill: var(--svg-color--f5de19, #f5de19);
  d: path("M24.82 27.57a2.5 2.5 0 0 0 2.25 1.39c.94 0 1.55-.48 1.55-1.13c0-.78-.62-1.06-1.67-1.51l-.57-.25c-1.64-.7-2.74-1.58-2.74-3.44A3.05 3.05 0 0 1 27 19.62a3.4 3.4 0 0 1 3.24 1.83l-1.78 1.14A1.55 1.55 0 0 0 27 21.6a1 1 0 0 0-1.1.98c0 .68.43.96 1.4 1.38l.57.25c1.95.83 3.04 1.68 3.04 3.58c0 2.05-1.61 3.18-3.78 3.18a4.4 4.4 0 0 1-4.16-2.33Zm-8.06.2c.35.64.68 1.17 1.46 1.17c.75 0 1.23-.29 1.23-1.43v-7.76h2.28v7.79a3.1 3.1 0 0 1-3.4 3.44a3.5 3.5 0 0 1-3.43-2.09Z");
}

.l1q-mxfjf {
  stop-color: var(--svg-color--dbdb00, #dbdb00);
}

.oi4kq9b7z {
  stop-color: var(--svg-color--c1c100, #c1c100);
}

.oq05-nbzl {
  fill: var(--svg-color--c1c100, #c1c100);
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("m29.24 6.66l-.96 15.01l-9.14-19.69zm-6.33 19.41L16 30.01l-6.9-3.94l1.4-3.4h11zM16 9.46l3.62 8.8h-7.24zM3.7 21.67L2.77 6.66l10.1-4.67z");
}

.qvdjvbboh {
  d: path("m222.08 39.2l-8.02 125.91L137.4 0zM168.98 202l-57.94 33.06L53.11 202l11.78-28.55h92.3zM111.04 62.67l30.36 73.8H80.68zM7.94 165.11L.01 39.2L84.7 0z");
}

</style>
