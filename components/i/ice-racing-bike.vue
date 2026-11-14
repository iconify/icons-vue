<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qah56obyw"/><path class="jujijob5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ice-racing-bike" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jujijob5d {
  d: path("M5.5 8.5L8 5h4.75l1.75 3.5Zm12 0L15.25 3h2.5M18 14.75v6.75m-3-5l6 3.25m-6 0l6-3.25m-4.25-1L18 16.75l1.25-1.25m-2.5 5.25L18 19.5l1.25 1.25");
}

.qah56obyw {
  d: path("M2 8.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m12 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
