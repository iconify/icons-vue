<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kwocv2o6o"/><path class="kt40boc5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bowling-finger-holes" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kt40boc5x {
  d: path("M10 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5.5-4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.kwocv2o6o {
  d: path("M3 21.5A18.5 18.5 0 0 1 21.5 3");
}

</style>
