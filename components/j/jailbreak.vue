<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p82v1cc5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jailbreak" /></template>
<style>
.p82v1cc5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11h6a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-6A3.5 3.5 0 0 1 3 18v-3.5A3.5 3.5 0 0 1 6.5 11m6 0V6.5a3.75 3.75 0 0 1 7.5 0v3m-10.5 5V18M5.25 8.25L3.5 6.5m5 1.5V5.5");
}

</style>
