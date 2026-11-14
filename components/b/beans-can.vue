<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h22zqwbfr"/><path class="vq7gpsb7h"/><path class="hvfsryq8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beans-can" /></template>
<style>
.h22zqwbfr {
  d: path("M5.5 5.5a6.5 2 0 1 0 13 0a6.5 2 0 1 0-13 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvfsryq8e {
  d: path("M9.5 13.5c-1-2 1-3.75 3-3c1 .4 2-.25 2.5.5c.75 1.5-1 4-3.25 4c-1 0-1.85-.7-2.25-1.5");
}

.vq7gpsb7h {
  d: path("M5.5 5.5v13a6.5 2 0 0 0 13 0v-13");
}

</style>
