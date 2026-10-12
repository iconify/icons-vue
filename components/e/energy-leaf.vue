<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fjew3ulav"/><path class="on2l05blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:energy-leaf" /></template>
<style>
.fjew3ulav {
  d: path("M8 7.5h8q1.5 0 1.5 1.5v1.5q0 1.5-.99 2.63l-1.52 1.74Q14 16 12.5 16h-1q-1.5 0-2.49-1.13l-1.52-1.74Q6.5 12 6.5 10.5V9q0-1.5 1.5-1.5m1.5 0V3m4 4.5V3M12 16v5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.on2l05blb {
  d: path("M16.75 8.25C17 4.93 18 3.25 21.25 3C21 6.32 20 8 16.75 8.25");
}

</style>
