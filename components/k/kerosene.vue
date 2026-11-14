<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2dze70ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kerosene" /></template>
<style>
.s2dze70ia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 10h7.25a2.625 2.625 0 0 1 2.625 2.625v5.75A2.625 2.625 0 0 1 12.875 21h-7.25A2.625 2.625 0 0 1 3 18.375v-5.75A2.625 2.625 0 0 1 5.625 10M5 10V7.5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1V10m3 0l5-6h2.5M20 8s1.75 2.25 1.75 3.25a1.75 1.75 0 0 1-3.5 0C18.25 10.25 20 8 20 8");
}

</style>
