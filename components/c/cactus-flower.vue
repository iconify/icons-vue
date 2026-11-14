<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1tv4hyax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cactus-flower" /></template>
<style>
.c1tv4hyax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21.5V6a2.5 2.5 0 0 1 5 0v15.5M7 15H5.5A2.5 2.5 0 0 1 3 12.5V9m9 4h4a2.5 2.5 0 0 0 2.5-2.5V9m0 0c-2.5 0-3-2-3-4.5c1.25 0 2.25.5 2.5 1c0-1.5.25-2.5.5-3c.25.5.5 1.5.5 3c.25-.5 1.25-1 2.5-1c0 2.5-.5 4.5-3 4.5");
}

</style>
