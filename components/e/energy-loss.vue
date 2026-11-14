<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6jyte48q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-loss" /></template>
<style>
.t6jyte48q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.625 11h.75A2.625 2.625 0 0 1 15 13.625v2.75A2.625 2.625 0 0 1 12.375 19h-.75A2.625 2.625 0 0 1 9 16.375v-2.75A2.625 2.625 0 0 1 11.625 11M2.5 15h3.75m-2-2l2 2l-2 2m13.5-2h3.75m-1.75-1.5L21.5 15l-1.75 1.5M10.25 8c-1.25-1.25 1.25-2.75 0-4.5m4 4.5c-1.25-1.25 1.25-2.75 0-4.5");
}

</style>
