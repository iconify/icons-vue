<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ku-acvbqq"/><path class="gagpxubwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-wheel-ramp" /></template>
<style>
.gagpxubwp {
  d: path("M5.5 15L9 9.25l4.5-1.75l2 3.75m-2-3.75L12.75 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ku-acvbqq {
  d: path("m2.5 19.5l19-7.5m-19 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0m10-3.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
