<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d7pue0sgm"/><path class="gy5poyn3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:house-number-plate" /></template>
<style>
.d7pue0sgm {
  d: path("M6.5 9h11a3.5 3.5 0 0 1 3.5 3.5v5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5v-5A3.5 3.5 0 0 1 6.5 9m0-2.75L12 2.5l5.5 3.75");
}

.gy5poyn3y {
  d: path("M13.5 18.25v-6.5L9.5 16H16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
