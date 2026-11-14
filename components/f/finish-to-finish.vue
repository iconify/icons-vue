<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy8h7ubqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:finish-to-finish" /></template>
<style>
.fy8h7ubqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 4h9a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 13.75 8h-9A1.75 1.75 0 0 1 3 6.25v-.5A1.75 1.75 0 0 1 4.75 4m5 12h4a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 13.75 20h-4A1.75 1.75 0 0 1 8 18.25v-.5A1.75 1.75 0 0 1 9.75 16M15.5 6h5v12h-5");
}

</style>
