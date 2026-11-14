<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snj5dob5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:avalanche-dog" /></template>
<style>
.snj5dob5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9h8l2-4h3.5l2 2.5L19 9v4.5a2 2 0 0 1-2 2H6A3.25 3.25 0 0 1 6 9Zm-.5 6.5V19M9 15.5V19m5-3.5V19m3.5-3.5V19m-14-9l-1-3m8 4v2.5m-1.25-1.25h2.5");
}

</style>
