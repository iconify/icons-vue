<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iz_lr-hnc"/><rect class="vfcwvdbfr"/><path class="w4vch7bet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kitchen-sink" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iz_lr-hnc {
  d: path("M12 8.25V5a2.25 2.25 0 0 1 4.5 0v.75");
}

.vfcwvdbfr {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 8.25px;
  rx: 2.5px;
}

.w4vch7bet {
  d: path("M6.5 11h3q1.25 0 1.25 1.25v5q0 1.25-1.25 1.25h-3q-1.25 0-1.25-1.25v-5Q5.25 11 6.5 11m8 0h3q1.25 0 1.25 1.25v5q0 1.25-1.25 1.25h-3q-1.25 0-1.25-1.25v-5q0-1.25 1.25-1.25");
}

</style>
