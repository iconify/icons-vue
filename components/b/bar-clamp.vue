<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="djmm2yb5t"/><path class="xgbgy6bav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bar-clamp" /></template>
<style>
.djmm2yb5t {
  d: path("M4 2.5h3v19H4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xgbgy6bav {
  d: path("M4 3.5h15v3H4ZM4 16h13v3H4Zm11-6.5v12m-2-12h4");
}

</style>
