<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pupdmghsa"/><path class="nx85z4z5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guitar-pickup" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nx85z4z5d {
  d: path("M5.75 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.pupdmghsa {
  d: path("M6.5 8h11a4 4 0 0 1 4 4a4 4 0 0 1-4 4h-11a4 4 0 0 1-4-4a4 4 0 0 1 4-4M7 4.5v15m5-15v15m5-15v15");
}

</style>
