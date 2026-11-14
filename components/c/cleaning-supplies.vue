<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8zkb7j-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cleaning-supplies" /></template>
<style>
.a8zkb7j-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 9h14.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25H4.75a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 4.75 9M5 11.5L6.5 21h11l1.5-9.5M14 9l3.5-6.5m-9.25 2zA1.75 1.75 0 0 1 10 6.25v1A1.75 1.75 0 0 1 8.25 9A1.75 1.75 0 0 1 6.5 7.25v-1A1.75 1.75 0 0 1 8.25 4.5");
}

</style>
