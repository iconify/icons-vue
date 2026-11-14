<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td61b9bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:check-out-done" /></template>
<style>
.td61b9bgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17a4 4 0 1 0 8 0a4 4 0 1 0-8 0m6.75-2.75L20.5 3.5m-3 3l1.75 1.75M15 9l1.75 1.75m-2 7.25l2 2L21 15.75");
}

</style>
