<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hocni59ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lawsuit" /></template>
<style>
.hocni59ak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.464 8L9 4.464a2.5 2.5 0 0 1 3.536 0a2.5 2.5 0 0 1 0 3.536L9 11.536a2.5 2.5 0 0 1-3.536 0a2.5 2.5 0 0 1 0-3.536m5.286 1.75L19 18M4.75 18h6.5A1.75 1.75 0 0 1 13 19.75a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 3 19.75A1.75 1.75 0 0 1 4.75 18");
}

</style>
