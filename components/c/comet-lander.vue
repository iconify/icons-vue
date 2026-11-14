<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm685ce2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:comet-lander" /></template>
<style>
.lm685ce2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11C3.5 7.5 6 5 9 5.5c2.5-1 5.5 1.5 5 4.5c1 3-1.5 6.5-4.5 6c-3 1-6-1.5-6-5m12.75-5.5l4.5-2.25m-3.5 6.25l4.25-2.25M15 18.5a3 3 0 0 1 6 0Zm.75 0l-1.5 3m6-3l1.5 3");
}

</style>
