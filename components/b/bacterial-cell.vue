<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js_e0khnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bacterial-cell" /></template>
<style>
.js_e0khnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8h4a4 4 0 0 1 4 4a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4a4 4 0 0 1 4-4m8 4q1.75-3.5 3.5 0t3.5 0");
}

</style>
