<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyadr39jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hydrogen-network" /></template>
<style>
.wyadr39jt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2v11m-2 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0M5 9h10.5m0 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M14 15.5v6m3.5-6v6m-3.5-3h3.5m2.75.5A.875.875 0 0 1 22 19c0 1-1.75 1.5-1.75 2.5H22");
}

</style>
