<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xigeg_uul"/><path class="w4i272bcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ear-cross-section" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w4i272bcr {
  d: path("M10 9.5a2.25 2.25 0 0 1 4.5 0c0 2.5-2.5 3-3 5");
}

.xigeg_uul {
  d: path("M6 9c0-4 2.5-6.5 6-6.5S18 5 18 9c0 3-2.5 4.5-3.5 6.5s-.5 6-4.5 6c-2.5 0-3.5-2-3.5-3.5");
}

</style>
