<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn5pr6q0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beard-oil" /></template>
<style>
.vn5pr6q0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10.5H10a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5H6.5A3.5 3.5 0 0 1 3 18v-4a3.5 3.5 0 0 1 3.5-3.5M7 7h2.5A1.5 1.5 0 0 1 11 8.5V9a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 9v-.5A1.5 1.5 0 0 1 7 7m-.5 0V4.5a1.75 1.75 0 0 1 3.5 0V7m9 2s2.5 3.25 2.5 5a2.5 2.5 0 0 1-5 0c0-1.75 2.5-5 2.5-5");
}

</style>
