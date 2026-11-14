<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evynwnb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:goal-conversion" /></template>
<style>
.evynwnb7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4c2.5-1.25 4.5 1.25 7 0s4.5 1.25 7 0v8.5c-2.5 1.25-4.5-1.25-7 0s-4.5-1.25-7 0M5 3v18.5m9.5-3.5l2.5 2.5l4.5-5");
}

</style>
