<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rwk30eb-i"/><path class="ml2q1yt_k"/><rect class="dk5gmka8x"/><path class="i8c80ablh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gas-station" /></template>
<style>
.dk5gmka8x {
  width: 4.5px;
  height: 10.5px;
  x: 7px;
  y: 10.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8c80ablh {
  d: path("M11.5 13H13a1 1 0 0 1 1 1v3.5a1.5 1.5 0 0 0 3 0v-5l-1.25-1.25");
}

.ml2q1yt_k {
  d: path("M4 7v14.25M20 7v14.25m-17.25 0h18.5");
}

.rwk30eb-i {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 3px;
  rx: 1.25px;
}

</style>
