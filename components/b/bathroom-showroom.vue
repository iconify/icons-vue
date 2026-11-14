<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tsjqhoq0r"/><path class="dib3l5w8e"/><path class="uwo084fft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bathroom-showroom" /></template>
<style>
.dib3l5w8e {
  d: path("M5.25 10.75v9.75h7.35m6.15-7.85v-1.9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tsjqhoq0r {
  d: path("m3 8.5l1.5-5h15l1.5 5a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0");
}

.uwo084fft {
  d: path("M8 20.5v-5h3.2m.8 4.2v.8m2-5h8v1.25a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Zm2 4l-.75 2.25M20 19.5l.75 2.25");
}

</style>
