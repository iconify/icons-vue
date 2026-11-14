<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="epjm6xbhj"/><path class="uag740b4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:element-carbon" /></template>
<style>
.epjm6xbhj {
  d: path("M7.829 3.5h8.342a1.75 1.75 0 0 1 1.354.642l3.064 3.744a1.75 1.75 0 0 1-.005 2.223l-7.235 8.758a1.75 1.75 0 0 1-2.698 0l-7.235-8.758a1.75 1.75 0 0 1-.005-2.223l3.064-3.744A1.75 1.75 0 0 1 7.829 3.5M2.5 9h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uag740b4g {
  d: path("M9.5 3.5L8 9l4 11.5m2.5-17L16 9l-4 11.5");
}

</style>
