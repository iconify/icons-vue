<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ro9hzibkw"/><path class="ailkgzb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airport-rail-link" /></template>
<style>
.ailkgzb_m {
  d: path("M8 5.5h2.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 10.5 10H8a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 8 5.5m-1 8.25h.01m4.49 0h.01m7.24.25v7.75M15.5 19.5l3.25-2.25L22 19.5m-5 2.25h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ro9hzibkw {
  d: path("M8.75 2.5h1A5.25 5.25 0 0 1 15 7.75v4A5.25 5.25 0 0 1 9.75 17h-1a5.25 5.25 0 0 1-5.25-5.25v-4A5.25 5.25 0 0 1 8.75 2.5M7 17l-1.5 4m6-4l1.5 4");
}

</style>
