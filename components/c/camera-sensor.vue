<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uk7g0-bpu"/><path class="bklc6zr3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-sensor" /></template>
<style>
.bklc6zr3s {
  d: path("M8.75 8.5h6.5A1.75 1.75 0 0 1 17 10.25v3.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 13.75v-3.5A1.75 1.75 0 0 1 8.75 8.5M8 2.5v3m4-3v3m4-3v3m-8 13v3m4-3v3m4-3v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uk7g0-bpu {
  d: path("M7.5 5.5h9A3.5 3.5 0 0 1 20 9v6a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 15V9a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
