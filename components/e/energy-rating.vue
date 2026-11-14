<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnw4nccja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-rating" /></template>
<style>
.qnw4nccja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h3l3 1.5l-3 1.5h-3zm0 5.25h7l3 1.5l-3 1.5h-7zm0 5.25h11l3 1.5l-3 1.5h-11zm0 5.25h15l3 1.5l-3 1.5h-15z");
}

</style>
