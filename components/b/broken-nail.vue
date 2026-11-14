<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zafg-cchn"/><path class="trbpac85q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:broken-nail" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.trbpac85q {
  d: path("M9 18q3-2.5 6 0");
}

.zafg-cchn {
  d: path("M6.5 9c0-3.75 2.25-6 5.5-6h.5l1.25 3l1.5-1.25L16 7.5l1.5 1V16a5.5 5.5 0 0 1-11 0Z");
}

</style>
