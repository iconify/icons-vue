<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv1ujbk6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bookshelf" /></template>
<style>
.jv1ujbk6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21h18M3 11.5h18M6 4za1.5 1.5 0 0 1 1.5 1.5V10A1.5 1.5 0 0 1 6 11.5A1.5 1.5 0 0 1 4.5 10V5.5A1.5 1.5 0 0 1 6 4m4.5 1.5zA1.5 1.5 0 0 1 12 7v3a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 9 10V7a1.5 1.5 0 0 1 1.5-1.5M15 4za1.5 1.5 0 0 1 1.5 1.5V10a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5V5.5A1.5 1.5 0 0 1 15 4M6.5 14zA1.5 1.5 0 0 1 8 15.5v4A1.5 1.5 0 0 1 6.5 21A1.5 1.5 0 0 1 5 19.5v-4A1.5 1.5 0 0 1 6.5 14m5 1.5zA1.5 1.5 0 0 1 13 17v2.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5V17a1.5 1.5 0 0 1 1.5-1.5m4.314 4.033l.862-4.021a1.495 1.495 0 0 1 1.824-1.137l.058.015a1.5 1.5 0 0 1 1.095 1.805l-.877 3.655A1.5 1.5 0 0 1 17.317 21H17a1.213 1.213 0 0 1-1.186-1.467");
}

</style>
