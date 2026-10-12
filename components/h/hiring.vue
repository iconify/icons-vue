<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="yredinz1h"/><path class="ik7yh4bnl"/><rect class="l9dmk0azu"/><path class="shdx4s2dx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hiring" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ik7yh4bnl {
  d: path("M3.5 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S2.75 16.5 2.75 19.5a.75.75 0 0 0 .75.75");
}

.l9dmk0azu {
  width: 5.75px;
  height: 4.75px;
  x: 15.5px;
  y: 7.25px;
  rx: 1.25px;
}

.shdx4s2dx {
  d: path("M17 7.25v-1.5a1 1 0 0 1 1-1h.75a1 1 0 0 1 1 1v1.5");
}

.yredinz1h {
  cx: 9px;
  cy: 7.75px;
  r: 3.75px;
}

</style>
