<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu72skb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electric-guitar" /></template>
<style>
.gu72skb7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 11.75c-.5-1-.25-2.5.5-3c-2 0-3.25 1.75-4.75 2.25c-3 1-4.5 4-3.5 7.5c.75 2.5 4 3.25 6.5 2c2-1 2.75-2.75 3.5-3c.5-1.5 1.75-2.25 2.25-4.75c-.5 0-2 0-3 .5Zm.75.75l6.25-6.25m-.091-1.427l1.414-1.414a1.25 1.25 0 0 1 1.768 0a1.25 1.25 0 0 1 0 1.768l-1.414 1.414a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768M6.75 14.75l2.5 2.5");
}

</style>
