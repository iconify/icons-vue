<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ppmlho6cz"><path class="aqim42u8n"/><path class="je_rgpbij"/><path class="h5c9tvgfr"/><path class="ew6w60b4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-fresh" /></template>
<style>
.aqim42u8n {
  fill: var(--svg-color--ffdb1e, #ffdb1e);
  d: path("M28.15 6.64c4.03 9.85 0 15.15-3.43 18.07c.84 2.92-2.49 3.52-3.75 2.08a17.1 17.1 0 0 1-16.7-4.17c-2.91-2.92-.63-9.42 7.1-13.77c6.68-3.76 13.36-5.83 16.77-2.21");
}

.ew6w60b4w {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.62 13.02c.82-.63 1.38-.84 1.75-2.1c.48.1.7-.08 1.09-.6c.26.4 1.38.51 2.03.6c-.59.37-.88.7-1.2 1.75a4.3 4.3 0 0 0-3.67.35");
}

.h5c9tvgfr {
  fill: var(--svg-color--ffe600, #ffe600);
  d: path("M23.5 6.58c3.88 1.04-.3 4.75-3.59 7.12a44 44 0 0 1-6.6 4.03c-.31.15-1.36-1.88-1.36-.83c0 .34-.58 1.87-.78 1.94A18 18 0 0 1 6.3 19.9c-2.91 0-1.61-3.97 2.5-7.6c.76-.67 1.24-.55 1.91-.55c-.44-.64-.44-.76.34-1.28c3.48-2.34 7.82-3.9 9.67-4.2c.3 0 .7.3.7.52a7 7 0 0 1 2.07-.22");
}

.je_rgpbij {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--ffdb1e, #ffdb1e);
  stroke-width: var(--svg-stroke-width--0-83px, 0.83px);
  d: path("M11.38 8.85c5.7-3.76 12.54-5.32 15.33-2.9c4.27 3.74-9.08 12.17-14.08 14.17c-5.43 2.15-2.5 7.1-5.43 7.1c-2.5 0-2.08-3.35-4.32-6.48c-1.32-1.85 1.96-7.6 8.5-11.9z");
}

.ppmlho6cz {
  stroke-width: var(--svg-stroke-width--0-84px, 0.84px);
}

</style>
