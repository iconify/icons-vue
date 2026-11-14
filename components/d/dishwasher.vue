<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wv8qurw0q"/><path class="m01g6kb8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dishwasher" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m01g6kb8p {
  d: path("M8.5 14.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M7.5 6h.01");
}

.wv8qurw0q {
  d: path("M7.5 3.5h9A3.5 3.5 0 0 1 20 7v10a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 17V7a3.5 3.5 0 0 1 3.5-3.5M4 8.5h16");
}

</style>
