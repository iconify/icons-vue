<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km5yz9bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dynamic-mic" /></template>
<style>
.km5yz9bqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 11.5a5 5 0 1 1 6 0l-1.5 9a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1Zm0 0h6m-8-4h10");
}

</style>
