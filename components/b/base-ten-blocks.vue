<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urcinexur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:base-ten-blocks" /></template>
<style>
.urcinexur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9.5zA1.5 1.5 0 0 1 6 11v8a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 3 19v-8a1.5 1.5 0 0 1 1.5-1.5m6-6.5h9A1.5 1.5 0 0 1 21 4.5v9a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 9 13.5v-9A1.5 1.5 0 0 1 10.5 3M9 7h12M9 11h12m-8-8v12m4-12v12");
}

</style>
