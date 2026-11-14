<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bws-gfbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hypothermia-alert" /></template>
<style>
.bws-gfbvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 14.5V5a2.5 2.5 0 0 1 5 0v9.5a4 4 0 1 1-5 0M8 12v5.5M17 4v6m-2.5-4.5l5 3m-5 0l5-3m-1.5 9V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
