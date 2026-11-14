<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab-x4bc3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:co2-molecule" /></template>
<style>
.ab-x4bc3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M2.5 12A2.25 2.25 0 1 0 7 12a2.25 2.25 0 1 0-4.5 0M17 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M7 12h1.75m6.5 0H17");
}

</style>
