<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="jtgf3rbha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:element-europium" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.jtgf3rbha {
  d: path("M10.25 8H6.5v8h3.75M6.5 12h3.25m3.5-1v3a2 2 0 0 0 4 0v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
