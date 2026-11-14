<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_df9cbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bedroom" /></template>
<style>
.t_df9cbnd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11h11a3.5 3.5 0 0 1 3.5 3.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 14.5A3.5 3.5 0 0 1 6.5 11M3 18v2.5M21 18v2.5M7.25 7.5h2A1.75 1.75 0 0 1 11 9.25A1.75 1.75 0 0 1 9.25 11h-2A1.75 1.75 0 0 1 5.5 9.25A1.75 1.75 0 0 1 7.25 7.5m7.5 0h2a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 16.75 11h-2A1.75 1.75 0 0 1 13 9.25a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
