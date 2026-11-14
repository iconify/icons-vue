<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aww13kb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:egg-with-chick" /></template>
<style>
.aww13kb1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 13.5l2.25 2l2.25-2l2.5 2l2.5-2l2.25 2l2.25-2c0 5-3 8-7 8s-7-3-7-8M8 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m5.5-.75h.01");
}

</style>
