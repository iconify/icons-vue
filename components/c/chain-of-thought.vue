<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0ugf0b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chain-of-thought" /></template>
<style>
.h0ugf0b_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12h9.5a2.75 2.75 0 1 0-.5-5.5a4.6 4.6 0 0 0-9 0A2.75 2.75 0 0 0 9 12m-1.75 3.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-3 2.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0M3 21h.01");
}

</style>
