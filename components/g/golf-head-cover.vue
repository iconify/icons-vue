<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g4cl01-0i"/><path class="dcizx2b4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-head-cover" /></template>
<style>
.dcizx2b4m {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-5.5 14H10m-2.75 0v3");
}

.g4cl01-0i {
  d: path("M4.5 21.5V12c0-4 3-5.5 7.5-5.5c5 0 8.5 2 8.5 5.5c0 3-2.5 4.5-6 4.5H10v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
