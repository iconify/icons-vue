<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="duzev1j2b"/><path class="xdo6c8bac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diplomatic-pouch" /></template>
<style>
.duzev1j2b {
  d: path("M6 9h12a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 9M5 9c0-6.5 14-6.5 14 0M3.5 10l6.5 4m4 0l6.5-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdo6c8bac {
  d: path("M9.75 15.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
