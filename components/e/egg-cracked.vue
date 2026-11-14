<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n71uwuccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:egg-cracked" /></template>
<style>
.n71uwuccs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11.5L8 10l2.5 1.5L13 10l2.5 1.5l3-1.5c-.5-4.5-3-7.5-6.5-7.5s-6.25 3-6.5 9m0 3.5L8 13.5l2.5 1.5l2.5-1.5l2.5 1.5l3-1.5c0 5-3 8-6.5 8s-6.5-3-6.5-6.5");
}

</style>
