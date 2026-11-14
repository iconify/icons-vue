<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knha73bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:footprint-evidence" /></template>
<style>
.knha73bxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5c3 0 4.5 2.5 4.5 5.5c0 2.5-1.5 4-1.5 5.5H6c0-1.5-1.5-3-1.5-5.5C4.5 5 6 2.5 9 2.5M8.5 16h1a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 9.5 21h-1A2.5 2.5 0 0 1 6 18.5A2.5 2.5 0 0 1 8.5 16m7.009 3.11l.942-3.5A1.5 1.5 0 0 1 17.9 14.5h.7a1.5 1.5 0 0 1 1.449 1.11l.942 3.5A1.5 1.5 0 0 1 19.543 21h-2.586a1.5 1.5 0 0 1-1.448-1.89");
}

</style>
