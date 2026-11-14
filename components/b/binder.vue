<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m-3p87buf"/><path class="z-f1x7rrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:binder" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-3p87buf {
  d: path("M9.75 2.5h7a3.5 3.5 0 0 1 3.5 3.5v12a3.5 3.5 0 0 1-3.5 3.5h-7a3.5 3.5 0 0 1-3.5-3.5V6a3.5 3.5 0 0 1 3.5-3.5m-6 4H8.5M3.75 12H8.5m-4.75 5.5H8.5");
}

.z-f1x7rrc {
  d: path("M13 6h2.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 15.5 10H13a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 13 6");
}

</style>
