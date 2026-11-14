<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-fg9axpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bath-bomb" /></template>
<style>
.v-fg9axpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11.25a6 6 0 1 0 12 0a6 6 0 1 0-12 0M3 21q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0M18 3.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M15 2.5h.01");
}

</style>
