<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0_9-cbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bus-driver" /></template>
<style>
.e0_9-cbcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5V8a3.5 3.5 0 0 0 7 0V6.5m-8.5 0H16m-9 0v-1a3.5 3 0 0 1 7 0v1m-11 14c0-3.5 3.25-6 7.5-6c.732 0 1.434.074 2.096.215M14.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m0 0h7M18 18v3.5");
}

</style>
