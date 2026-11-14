<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt5a8jq-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hypothermia" /></template>
<style>
.pt5a8jq-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15V5.75a2.75 2.75 0 0 1 5.5 0V15A4 4 0 1 1 6 15m2.75-2.5V18M18 15v6m-2.5-4.5l5 3m-5 0l5-3");
}

</style>
