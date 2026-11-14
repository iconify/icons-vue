<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rcwmx8b0p"/><path class="i66aruydi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:length-limit-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i66aruydi {
  d: path("M9.5 9.75L7.25 12l2.25 2.25m5-4.5L16.75 12l-2.25 2.25");
}

.rcwmx8b0p {
  d: path("M2.25 12a9.75 9.75 0 1 0 19.5 0a9.75 9.75 0 1 0-19.5 0M5.5 9.5v5m13-5v5M7.25 12h9.5");
}

</style>
