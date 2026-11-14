<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2yw52bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:change-bed-sheets" /></template>
<style>
.p2yw52bsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5V18M3 7.5h15a2 2 0 0 1 2 2v2H3M7.25 4h1A1.75 1.75 0 0 1 10 5.75A1.75 1.75 0 0 1 8.25 7.5h-1A1.75 1.75 0 0 1 5.5 5.75A1.75 1.75 0 0 1 7.25 4M15 16.25h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

</style>
