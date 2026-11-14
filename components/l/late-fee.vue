<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynrhpu8gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:late-fee" /></template>
<style>
.ynrhpu8gp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h12m-12 19h9.7m-8.2-19V5c0 3.5 4.5 5 4.5 7s-4.5 3.5-4.5 7v2.5m9-19V5c0 3.5-4.5 5-4.5 7c0 1.391 2.176 2.54 3.502 4.287M7.25 21.5c0-2.25 5.5-2.25 5.5 0M20 16.25c-.25-.75-1-1.25-2-1.25c-1.1 0-1.75.6-1.75 1.5c0 1.75 3.75 1 3.75 3c0 .9-.75 1.5-2 1.5c-1 0-1.75-.5-2-1.25m2-6V15m0 6v1");
}

</style>
