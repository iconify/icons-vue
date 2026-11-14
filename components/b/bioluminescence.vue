<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm1yvjbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bioluminescence" /></template>
<style>
.fm1yvjbrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5c0-5.5 3-9 7-9s7 3.5 7 9Zm3 0q-1 2.5 0 4.5t0 4.5m4-9q-1 3 0 5.5t0 4.5m4-10q-1 2.25 0 4.5m5-.5q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3");
}

</style>
