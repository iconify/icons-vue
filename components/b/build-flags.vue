<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyt4ydbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:build-flags" /></template>
<style>
.fyt4ydbcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14V4.5c3-1.75 5.5 1.25 8.5 0c2.5-1 4-.75 6 0V14c-2-.75-3.5-1-6 0c-3 1.25-5.5-1.75-8.5 0m0 0v7");
}

</style>
