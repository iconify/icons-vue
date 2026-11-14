<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f09ok5rli"/><path class="ttgtvwbue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canopy-bed" /></template>
<style>
.f09ok5rli {
  d: path("M4 21V3.5h16V21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ttgtvwbue {
  d: path("M4 3.5q4 5 8 0q4 5 8 0M4 14h16M4 17.5h16m-11.25-7h1a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 9.75 14h-1A1.75 1.75 0 0 1 7 12.25a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
