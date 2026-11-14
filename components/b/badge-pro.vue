<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ekgcktb3t"/><path class="brodc4boe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badge-pro" /></template>
<style>
.brodc4boe {
  d: path("M5 15V9h1.25a1.25 1.25 0 0 1 0 2.5H5m5.25 3.5V9h1.25a1.25 1.25 0 0 1 0 2.5h-1.25m1.25 0L13 15m2.75-3a1.5 3 0 1 0 3 0a1.5 3 0 1 0-3 0");
}

.ekgcktb3t {
  d: path("M6.375 6h11.25A4.375 4.375 0 0 1 22 10.375v3.25A4.375 4.375 0 0 1 17.625 18H6.375A4.375 4.375 0 0 1 2 13.625v-3.25A4.375 4.375 0 0 1 6.375 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
