<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dah32bcba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:device-cooling-down" /></template>
<style>
.dah32bcba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 3h9.75A2.625 2.625 0 0 1 18.5 5.625v5a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 3.5 10.625v-5A2.625 2.625 0 0 1 6.125 3M2.5 16.5h11.1m5.15-.5v5.5m-2.5-4.25l5 3m-5 0l5-3");
}

</style>
