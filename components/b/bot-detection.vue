<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4306rb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bot-detection" /></template>
<style>
.v4306rb8y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 7.5h3.25a4.375 4.375 0 0 1 4.375 4.375v.75A4.375 4.375 0 0 1 10.125 17h-3.25A4.375 4.375 0 0 1 2.5 12.625v-.75A4.375 4.375 0 0 1 6.875 7.5m1.625 0v-3m0-1h.01M6 12h.01M11 12h.01M6.5 14.75h4m4.75 2.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
