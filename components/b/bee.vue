<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="etn87cccw"/><path class="utruz3hys"/><path class="emisihbnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bee" /></template>
<style>
.emisihbnr {
  d: path("M2.5 9.5a3.5 2.25 0 1 0 7 0a3.5 2.25 0 1 0-7 0m12 0a3.5 2.25 0 1 0 7 0a3.5 2.25 0 1 0-7 0M11 4L9.5 2.5M13 4l1.5-1.5M7.5 13h9M8 16.5h8");
}

.etn87cccw {
  d: path("M10 5.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.utruz3hys {
  d: path("M7.5 14.25a4.5 6.25 0 1 0 9 0a4.5 6.25 0 1 0-9 0");
}

</style>
