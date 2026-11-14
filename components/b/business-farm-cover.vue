<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x2capjbjn"/><path class="n07_yuaoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:business-farm-cover" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n07_yuaoc {
  d: path("M7.25 14.5H8.5A1.5 1.5 0 0 1 10 16v3a1.5 1.5 0 0 1-1.5 1.5H7.25a1.5 1.5 0 0 1-1.5-1.5v-3a1.5 1.5 0 0 1 1.5-1.5m-1.5 0l4.25 6m0-6l-4.25 6M18 14.75L21 16v2.25c0 1.75-1.25 2.75-3 3.5c-1.75-.75-3-1.75-3-3.5V16Z");
}

.x2capjbjn {
  d: path("m4.114 9.976l6.75-5.757a1.75 1.75 0 0 1 2.272 0l6.75 5.757a1.75 1.75 0 0 1 .614 1.331v.068a.875.875 0 0 1-.875.875H14A1.75 1.75 0 0 0 12.25 14v4.75a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75v-7.443a1.75 1.75 0 0 1 .614-1.331");
}

</style>
