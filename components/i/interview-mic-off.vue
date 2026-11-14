<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctbau6bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:interview-mic-off" /></template>
<style>
.ctbau6bzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M3 21.5c0-4 3-6.25 6.5-6.25c1.173 0 2.289.253 3.256.739M17.75 3za1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 17.75 9A1.75 1.75 0 0 1 16 7.25v-2.5A1.75 1.75 0 0 1 17.75 3m0 6v3m-2.25 3.5l5 5m0-5l-5 5");
}

</style>
