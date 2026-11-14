<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqd8qx3ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beamed-sixteenths" /></template>
<style>
.lqd8qx3ee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 18.5a3 2.25 0 1 0 6 0a3 2.25 0 1 0-6 0Zm10 0a3 2.25 0 1 0 6 0a3 2.25 0 1 0-6 0Zm-4 0V4m10 14.5V4M10 4h10M10 7.5h10");
}

</style>
