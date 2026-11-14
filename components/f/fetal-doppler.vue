<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahjxtv3zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fetal-doppler" /></template>
<style>
.ahjxtv3zt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 4.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m6.798 16.046L13 21.5H7.5C7 18 6 15 6.25 12C6.5 9.5 6 8 7 7.5h3c1.5 0 2.25 1 2.5 2.5c1.623.406 2.514 1.69 2.555 3.099M14.25 18h1l1.25-2.5l1.75 5l1.5-2.5h2");
}

</style>
