<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1wekmhij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airpot" /></template>
<style>
.z1wekmhij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8.5h3.5A3.5 3.5 0 0 1 15 12v6a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18v-6A3.5 3.5 0 0 1 8 8.5m-3.5 0l2-3H13l2 3m-7.5-3v-3h7m.5 8h2.5L20 8");
}

</style>
