<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz5iarbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hyperparameters" /></template>
<style>
.xz5iarbmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5H6m4 0h11.5m-19 7H13m4 0h4.5m-19 7H8m4 0h9.5M6 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-5 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
