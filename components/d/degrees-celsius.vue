<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3bqk75_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:degrees-celsius" /></template>
<style>
.w3bqk75_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m15.678 11.479a6.5 6.5 0 1 1 0-9.958");
}

</style>
