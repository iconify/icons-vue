<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-yu_vbmz"/><path class="p6rbnpb0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:broken-heart-healing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-yu_vbmz {
  d: path("m12 20.5l-7.75-7.75A4.25 4.25 0 0 1 12 6.5a4.25 4.25 0 0 1 7.75 6.25Z");
}

.p6rbnpb0k {
  d: path("M12 6.5L10.75 9L12 11m0 3.5l1.25 2.5L12 20.5M10.25 11h3.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 10.25 11");
}

</style>
