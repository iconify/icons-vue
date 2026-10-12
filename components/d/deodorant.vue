<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sg71-5beq"/><rect class="pcobauxmc"/><path class="rl5m7zhwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deodorant" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pcobauxmc {
  width: 9.5px;
  height: 8.5px;
  x: 7.25px;
  y: 9.5px;
  rx: 2px;
}

.rl5m7zhwu {
  d: path("M10 12.25v3.5m.25 5.25h3.5");
}

.sg71-5beq {
  d: path("M8.75 6.5V5.25c0-1.5 1.45-2.5 3.25-2.5s3.25 1 3.25 2.5V6.5Z");
}

</style>
