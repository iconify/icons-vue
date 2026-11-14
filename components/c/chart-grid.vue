<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkdla-lry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-grid" /></template>
<style>
.jkdla-lry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3v18M7.5 3v18M12 3v18m4.5-18v18M21 3v18M3 3h18M3 7.5h18M3 12h18M3 16.5h18M3 21h18");
}

</style>
