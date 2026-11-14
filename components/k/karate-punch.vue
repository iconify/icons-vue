<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruihbybeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:karate-punch" /></template>
<style>
.ruihbybeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m3 5.5H18m1.75-1.75za1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 1 18 10.5a1.75 1.75 0 0 1 1.75-1.75M8.5 10l-1 5.5l-4 6m4-6L12 18v3.5");
}

</style>
