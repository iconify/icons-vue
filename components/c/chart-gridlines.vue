<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk-gaqbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-gridlines" /></template>
<style>
.qk-gaqbca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v17.5H21M5.5 8.5h2.25m2.75 0h2.75m3 0h3.25M5.5 14h2.25m2.75 0h2.75m3 0h3.25M9 3v3m0 4.5V12m0 4v2.5M15 3v3m0 4.5V12m0 4v2.5");
}

</style>
