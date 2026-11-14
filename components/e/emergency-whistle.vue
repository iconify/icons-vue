<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyluinbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-whistle" /></template>
<style>
.wyluinbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 9.5A5.5 5.5 0 1 1 9.75 13H3V9.5Zm-4.25-1.75a8.5 8.5 0 0 1 8.5 0M9.25 5a11.5 11.5 0 0 1 11.5 0");
}

</style>
