<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnpu-pt7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cursor-grabbing" /></template>
<style>
.bnpu-pt7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 13.5V8a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 3 0v5.5c0 3.6-2.4 6-5.5 6h-1c-1.9 0-3.2-.9-4.25-2.5L4 14.5a1.5 1.5 0 0 1 2-1M9 8v2.5M12 8v2.5M15 8v2.5");
}

</style>
