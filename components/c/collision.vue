<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy5n56inn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:collision" /></template>
<style>
.fy5n56inn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m9 0a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m0-10.5v4M7.75 6l1.5 2.25m7-2.25l-1.5 2.25");
}

</style>
