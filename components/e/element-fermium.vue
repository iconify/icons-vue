<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="q0zt8qu7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:element-fermium" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.q0zt8qu7r {
  d: path("M9.5 8H6v8m0-4h3m3 4v-3.5a1.5 1.5 0 0 1 3 0V16m0-3.5a1.5 1.5 0 0 1 3 0V16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
