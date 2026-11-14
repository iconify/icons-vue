<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krapefd-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gantt-shared" /></template>
<style>
.krapefd-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v19M7.5 3h8A1.5 1.5 0 0 1 17 4.5A1.5 1.5 0 0 1 15.5 6h-8A1.5 1.5 0 0 1 6 4.5A1.5 1.5 0 0 1 7.5 3m4 6h3a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-3a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 11.5 9m-4 6h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 9.5 18h-2A1.5 1.5 0 0 1 6 16.5A1.5 1.5 0 0 1 7.5 15m11.25-.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-4.5 3.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m4.5 2.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-2.25-3.5l2.5-2m-2.5 3.5l2.5 1");
}

</style>
