<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm2582b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:head-check" /></template>
<style>
.fm2582b9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7C2.5 6.25 5.75 3 10 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5-.1 1-.75 1H17v1.536m-4 4.44V21.5m1.75-3.5l2 2L21 15.75");
}

</style>
