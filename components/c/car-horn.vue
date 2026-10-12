<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qcwlaob-j"/><circle class="r9vfbpq0q"/><path class="hfz6cmrkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-horn" /></template>
<style>
.hfz6cmrkp {
  d: path("M2.75 12h4.5m5 0h4.5m-7 2.5V19M19 8.5c.9 1 1.4 2.2 1.4 3.5s-.5 2.5-1.4 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qcwlaob-j {
  d: path("M16.75 12a7 7 0 1 1-14 0a7 7 0 0 1 14 0");
}

.r9vfbpq0q {
  cx: 9.75px;
  cy: 12px;
  r: 2.5px;
}

</style>
