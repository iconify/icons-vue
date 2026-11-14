<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl0zq6btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grand-piano" /></template>
<style>
.sl0zq6btz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5a2 2 0 0 1 2-2h4c1.5 0 2 2 3 4.5s7 4 7 8.5v3a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm0 12.5h16m-12 0V21m4-3.5V21m4-3.5V21");
}

</style>
