<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fe4dj7dzc"/><path class="x9gmn8bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:birthday-cake-candles" /></template>
<style>
.fe4dj7dzc {
  d: path("M7.5 12h9a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 17v-1.5A3.5 3.5 0 0 1 7.5 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x9gmn8bye {
  d: path("M4 15.25q2 1.75 4 0t4 0t4 0t4 0M8 8.75V12m4-3.25V12m4-3.25V12M8 5.75h.01m3.99 0h.01m3.99 0h.01");
}

</style>
