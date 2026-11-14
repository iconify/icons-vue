<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ty76xvbob"/><path class="odyyd5bsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ground-source-loop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.odyyd5bsc {
  d: path("M5.75 5L8 7.25L10.25 5m3.5 1.25L16 4l2.25 2.25");
}

.ty76xvbob {
  d: path("M2.5 10h19M8 4v11a4 4 0 0 0 8 0V4");
}

</style>
