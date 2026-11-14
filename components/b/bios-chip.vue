<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcdqv6f1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bios-chip" /></template>
<style>
.wcdqv6f1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 4.5h3.25A2.625 2.625 0 0 1 13 7.125v3.25A2.625 2.625 0 0 1 10.375 13h-3.25A2.625 2.625 0 0 1 4.5 10.375v-3.25A2.625 2.625 0 0 1 7.125 4.5M7.25 2v2.5m3-2.5v2.5m-3 8.5v2.5m3-2.5v2.5M2 7.25h2.5m-2.5 3h2.5m8.5-3h2.5m-2.5 3h2.5m-1.5 7.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
