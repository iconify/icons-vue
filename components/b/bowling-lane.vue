<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="growbwbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bowling-lane" /></template>
<style>
.growbwbyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 21.5l4-19m15 19l-4-19M7.25 14l1.25-1.5L9.75 14m1-4.5L12 8l1.25 1.5m1 4.5l1.25-1.5l1.25 1.5");
}

</style>
