<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkpy686fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-dashboard" /></template>
<style>
.zkpy686fh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6q9.5-6 19 0M2.75 10a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m14 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-5-3.5h.5A1.75 1.75 0 0 1 14 8.25v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 10 8.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-4 10.75a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m0 0h8.5m-4.25 0v4.25");
}

</style>
