<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aw9s4h4kk"/><path class="es-cc6b-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lawn-sprinkler-schedule" /></template>
<style>
.aw9s4h4kk {
  d: path("M11.5 10.5h1A1.5 1.5 0 0 1 14 12a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 12a1.5 1.5 0 0 1 1.5-1.5m.5 3v7M6.75 9a6 6 0 0 1 10.5 0");
}

.es-cc6b-h {
  d: path("M4.75 6a9.5 9.5 0 0 1 14.5 0M3.5 20.5h8.8m4.45-5h2.5A1.75 1.75 0 0 1 21 17.25v2.25a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.5v-2.25a1.75 1.75 0 0 1 1.75-1.75M15 17.75h6m-4.25-3.25V16m2.5-1.5V16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
