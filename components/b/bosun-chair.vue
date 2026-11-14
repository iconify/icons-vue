<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i5glcvhqr"/><path class="u6462pzyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bosun-chair" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5glcvhqr {
  d: path("M4 21.5v-18h11v8m-4 4l4-4l4 4");
}

.u6462pzyd {
  d: path("M11.5 15.5h7A1.5 1.5 0 0 1 20 17a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 10 17a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
