<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i0ax29bur"/><path class="gunqphxwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eco-train" /></template>
<style>
.gunqphxwf {
  d: path("M8.75 5.5h1.5A1.75 1.75 0 0 1 12 7.25v.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 7 7.75v-.5A1.75 1.75 0 0 1 8.75 5.5m-1.25 8h.01m3.99 0h.01m-4.01 4L6 21m5.5-3.5L13 21m3 .25c0-3.75 2-5.75 5.75-5.75c0 3.75-2 5.75-5.75 5.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0ax29bur {
  d: path("M9.25 2.5h.5A5.25 5.25 0 0 1 15 7.75v4.5a5.25 5.25 0 0 1-5.25 5.25h-.5A5.25 5.25 0 0 1 4 12.25v-4.5A5.25 5.25 0 0 1 9.25 2.5");
}

</style>
