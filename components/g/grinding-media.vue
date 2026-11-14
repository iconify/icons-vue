<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hco5svbxl"/><path class="xpy38j13s"/><path class="e5jfzabtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grinding-media" /></template>
<style>
.e5jfzabtj {
  d: path("M10 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hco5svbxl {
  d: path("M4.25 5a9.5 9.5 0 1 0 15.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpy38j13s {
  d: path("M8 14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
