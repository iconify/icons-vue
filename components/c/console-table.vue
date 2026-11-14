<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf-h_gb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:console-table" /></template>
<style>
.yf-h_gb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 4.5h15.5A1.25 1.25 0 0 1 21 5.75A1.25 1.25 0 0 1 19.75 7H4.25A1.25 1.25 0 0 1 3 5.75A1.25 1.25 0 0 1 4.25 4.5M5.5 7v13.5M18.5 7v13.5m-13-6h13");
}

</style>
