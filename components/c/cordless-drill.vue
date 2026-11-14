<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djalmpenj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cordless-drill" /></template>
<style>
.djalmpenj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5h6A3.5 3.5 0 0 1 16 7a3.5 3.5 0 0 1-3.5 3.5h-6A3.5 3.5 0 0 1 3 7a3.5 3.5 0 0 1 3.5-3.5M17.25 5za1.25 1.25 0 0 1 1.25 1.25v1.5A1.25 1.25 0 0 1 17.25 9A1.25 1.25 0 0 1 16 7.75v-1.5A1.25 1.25 0 0 1 17.25 5m1.25 2h3m-15 3.5L6 16m5-5.5l-.5 5.5M6 16h5a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 11 21H6a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 6 16");
}

</style>
