<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aae3gib9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-handshake" /></template>
<style>
.aae3gib9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4za1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 4 11a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 4 4m16 0za1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 20 11a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 20 4M5.5 5.5H8l3-2h3.5l4 3.5m-13 3l5 5q.112.058.232.1q.119.042.243.066q.125.024.251.03t.252-.006t.249-.043t.24-.078t.227-.112t.207-.143l.015-.011m.405-.474q.086-.15.142-.313t.08-.334q.023-.171.012-.343T13 13L9.75 9.75M18 21.5l-3.25-3.25A2 2 0 0 1 18 16a2 2 0 0 1 3.25 2.25Z");
}

</style>
