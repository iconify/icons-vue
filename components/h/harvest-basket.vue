<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m6owtmb7h"/><circle class="v_-6mkj3f"/><circle class="xro3efbce"/><path class="ev21mpnel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:harvest-basket" /></template>
<style>
.ev21mpnel {
  d: path("M8.75 10.5V9.25m6.5 1.25V9.25M3.75 14.5h16.5q1 0 .68.95l-1.61 4.85q-.32.95-1.32.95H6q-1 0-1.32-.95l-1.61-4.85q-.32-.95.68-.95m.1 3.35h16.3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m6owtmb7h {
  d: path("M3.75 14.5a8.25 8.25 0 0 1 16.5 0");
}

.v_-6mkj3f {
  cx: 8.75px;
  cy: 12.5px;
  r: 2px;
}

.xro3efbce {
  cx: 15.25px;
  cy: 12.5px;
  r: 2px;
}

</style>
