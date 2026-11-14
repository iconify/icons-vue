<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s59spl4ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:earthquake-assembly" /></template>
<style>
.s59spl4ju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2 8.75c0-2.5 1.75-4 4-4s4 1.5 4 4M2.5 19a9.5 2.5 0 1 0 19 0a9.5 2.5 0 1 0-19 0M5 5.5L2.75 8L5 10.5L2.75 13M19 5.5L21.25 8L19 10.5l2.25 2.5");
}

</style>
