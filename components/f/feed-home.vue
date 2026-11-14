<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="se7c0ze5s"/><path class="unw48dbla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:feed-home" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.se7c0ze5s {
  d: path("m3.498 9.212l6.875-5.428a2.625 2.625 0 0 1 3.254 0l6.875 5.428a2.63 2.63 0 0 1 .998 2.06v7.603a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875v-7.603a2.63 2.63 0 0 1 .998-2.06");
}

.unw48dbla {
  d: path("M8.5 9.75h7a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-7a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5m0 5.75h7A1.5 1.5 0 0 1 17 17a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 17a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
