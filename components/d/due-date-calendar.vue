<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xtgvov5po"/><path class="d3dgu_bbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:due-date-calendar" /></template>
<style>
.d3dgu_bbg {
  d: path("m12 18l-3-3c-1.25-1.25-.75-3 1-3c1 0 1.5.5 2 1.25c.5-.75 1-1.25 2-1.25c1.75 0 2.25 1.75 1 3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xtgvov5po {
  d: path("M6.5 4.5h11A3.5 3.5 0 0 1 21 8v9.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5V8a3.5 3.5 0 0 1 3.5-3.5m1.5-2v4m8-4v4M3 9h18");
}

</style>
