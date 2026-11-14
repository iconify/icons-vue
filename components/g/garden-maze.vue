<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i2r69kxgu"/><path class="t0uti_2sg"/><path class="ydw1ymv3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-maze" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2r69kxgu {
  d: path("M21.25 10.25a9.5 9.5 0 1 0 0 3.5");
}

.t0uti_2sg {
  d: path("M5.75 13.75a6.5 6.5 0 1 0 0-3.5");
}

.ydw1ymv3x {
  d: path("M15 10.5a3.5 3.5 0 1 0 0 3m-3 5v3m0-16v3");
}

</style>
