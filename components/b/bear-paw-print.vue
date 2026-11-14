<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryvc_0bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bear-paw-print" /></template>
<style>
.ryvc_0bsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 16a6.5 5 0 1 0 13 0a6.5 5 0 1 0-13 0m-3-6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m2.75-4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.25-2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.25 2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18.5 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
