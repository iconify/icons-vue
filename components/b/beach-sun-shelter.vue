<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rway3tofh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beach-sun-shelter" /></template>
<style>
.rway3tofh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11a9.5 8 0 0 1 19 0a3.25 2 0 0 0-6.25 0a3.25 2 0 0 0-6.5 0a3.25 2 0 0 0-6.25 0ZM12 9v10m-7 2.5q7-5 14 0");
}

</style>
