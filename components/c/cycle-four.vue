<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky_k67b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cycle-four" /></template>
<style>
.ky_k67b0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4h10m-2-2l2 2l-2 2m5 1v10m-2-2l2 2l2-2m-5 5H7m2-2l-2 2l2 2m-5-5V7M2 9l2-2l2 2");
}

</style>
