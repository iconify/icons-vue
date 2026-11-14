<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxm2xwbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:finance-controller" /></template>
<style>
.oxm2xwbnh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3.5 21c0-4 3.25-6.5 7.5-6.5c1.5 0 2.75.25 4 .75M14.75 18l2 2L21 15.75");
}

</style>
