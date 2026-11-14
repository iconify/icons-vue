<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v792y1grz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drone-remote-id" /></template>
<style>
.v792y1grz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 13.5h3v3h-3Zm-1.75-1.75l1.75 1.75m4.75-1.75L13.5 13.5m-4.75 4.75l1.75-1.75m4.75 1.75L13.5 16.5m-8.25-6.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-9.5 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M10.25 6.5a4 4 0 0 1 3.5 0M9 3.75a7 7 0 0 1 6 0");
}

</style>
