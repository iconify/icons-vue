<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pscjkuumj"/><path class="r1ynu1bqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-ball-washer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pscjkuumj {
  d: path("M7.5 14a6 6 0 1 1 9 0");
}

.r1ynu1bqr {
  d: path("M3 14q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0M3 18.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0M12 7h.01m-2.26 3h.01m4.49 0h.01");
}

</style>
