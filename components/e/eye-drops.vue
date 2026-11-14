<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5o5ke2fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eye-drops" /></template>
<style>
.g5o5ke2fn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9.5za4 4 0 0 1 4 4V17a4 4 0 0 1-4 4a4 4 0 0 1-4-4v-3.5a4 4 0 0 1 4-4m0-7v7M18 7s-2 2.75-2 4.25a2 2 0 0 0 4 0C20 9.75 18 7 18 7");
}

</style>
