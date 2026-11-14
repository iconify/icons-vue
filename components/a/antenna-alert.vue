<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eotj7rg5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:antenna-alert" /></template>
<style>
.eotj7rg5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M10 8v13.5m-4.5-19a6 6 0 0 0 0 8m9-8a6 6 0 0 1 0 8m3.5 4V18m0 3h.01");
}

</style>
