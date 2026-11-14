<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxzzouuar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:defendant" /></template>
<style>
.cxzzouuar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M2.5 21c0-4 3-6.5 6.5-6.5c2.069 0 3.963.874 5.166 2.414M19 14.232L20.768 16a1.25 1.25 0 0 1 0 1.768a1.25 1.25 0 0 1-1.768 0L17.232 16a1.25 1.25 0 0 1 0-1.768a1.25 1.25 0 0 1 1.768 0M18 17l-3.25 3.25");
}

</style>
