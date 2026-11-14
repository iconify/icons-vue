<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8u760b4u"/><path class="ccwz0bbfl"/><path class="ccwzn6o3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-series" /></template>
<style>
.ccwz0bbfl {
  d: path("M6.5 11c2.5-6 5-6 7-2.5s4.5 3 7-2.5");
}

.ccwzn6o3i {
  d: path("M6.5 17c2.5-6 5-6 7-2.5s4.5 3 7-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p8u760b4u {
  d: path("M3.5 3v17.5H21");
}

</style>
