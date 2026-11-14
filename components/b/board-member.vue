<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3ut88but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:board-member" /></template>
<style>
.e3ut88but {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M5 15.5c0-2.25 3.25-3.25 7-3.25s7 1 7 3.25M6.5 19.875l.174-.566a1.5 1.5 0 0 1 1.434-1.059h7.784a1.5 1.5 0 0 1 1.434 1.059l.174.566a1.256 1.256 0 0 1-1.2 1.625H7.7a1.256 1.256 0 0 1-1.2-1.625");
}

</style>
