<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgzkpsbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dhoti" /></template>
<style>
.cgzkpsbtj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5h9A1.5 1.5 0 0 1 18 4a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 4a1.5 1.5 0 0 1 1.5-1.5m-.5 3L3 21l4.25-1.5L12 21l4.75-1.5L21 21L17 5.5m-7 0l-2.75 14M14 5.5l2.75 14");
}

</style>
