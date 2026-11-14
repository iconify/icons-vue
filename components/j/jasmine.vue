<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u04bc4b3y"/><path class="trc81unxh"/><path class="k5eayweyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jasmine" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k5eayweyv {
  d: path("M7.5 14.25Q3 14 3.5 9.5q4.5.5 4 4.75");
}

.trc81unxh {
  d: path("M4 21q3-8 8.25-11.25");
}

.u04bc4b3y {
  d: path("M12.25 9.75a1.75 1.75 0 1 1-.5-3A1.75 1.75 0 1 1 14.5 5.5a1.75 1.75 0 1 1 2 2a1.75 1.75 0 1 1-1.25 2.75a1.75 1.75 0 1 1-3-.5");
}

</style>
