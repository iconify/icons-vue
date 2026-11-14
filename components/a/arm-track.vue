<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rg7qsoywn"/><path class="x2ho6y6-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arm-track" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rg7qsoywn {
  d: path("M10.875 3h2.25A7.875 7.875 0 0 1 21 10.875v2.25A7.875 7.875 0 0 1 13.125 21h-2.25A7.875 7.875 0 0 1 3 13.125v-2.25A7.875 7.875 0 0 1 10.875 3");
}

.x2ho6y6-n {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
