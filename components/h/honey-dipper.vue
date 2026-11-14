<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfagdeb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:honey-dipper" /></template>
<style>
.wfagdeb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m7.75-3.25l6.5-6.5m-11.5 5.5l6 6m-8.5-3.5l6 6M6.75 16v5.5");
}

</style>
