<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd97l8zdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baseball-glove" /></template>
<style>
.nd97l8zdo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 21.5L6 16c-2-1.5-3-3.5-3-5.5c0-1.5 1.5-2 2.5-1l2 2.5V6c0-2.5 2-3.5 5-3.5c3.5 0 7 1.5 7 5.5v7c0 3-1.5 5-3 6.5Zm4-15v6m4-6v6");
}

</style>
