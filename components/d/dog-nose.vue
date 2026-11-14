<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx0eh1bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-nose" /></template>
<style>
.fx0eh1bgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7c0-3 3-3.5 6-3.5S18 4 18 7s-3.5 5-6 5s-6-2-6-5m6 5v3.5M4 14q.5 5 4.25 5T12 15.5q0 3.5 3.75 3.5T20 14");
}

</style>
