<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h981w4ppl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:keyboard-instrument" /></template>
<style>
.h981w4ppl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 4h13.75A2.625 2.625 0 0 1 21.5 6.625v3.75A2.625 2.625 0 0 1 18.875 13H5.125A2.625 2.625 0 0 1 2.5 10.375v-3.75A2.625 2.625 0 0 1 5.125 4M6 13v7.5M18 13v7.5M6.5 4v5m3-5v5m5-5v5m3-5v5");
}

</style>
