<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9ot57bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-to-value" /></template>
<style>
.w9ot57bwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11.75h17m-12.421 5.3l3-2.334a1.5 1.5 0 0 1 1.842 0l3 2.334a1.5 1.5 0 0 1 .579 1.184V20a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 20v-1.766a1.5 1.5 0 0 1 .579-1.184m5.671-12.3c-.25-.75-.85-1-1.75-1c-1.1 0-1.75.5-1.75 1.25c0 1.5 3.5 1 3.5 2.5c0 .75-.75 1.25-1.75 1.25s-1.65-.35-1.75-1M12 2.5v1.25m0 5v.75");
}

</style>
