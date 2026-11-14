<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2sgudbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drink-carrier" /></template>
<style>
.h2sgudbgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19V17a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Zm.5 0l-.5-7H7l-.5 7m3.75 0l-.5-7h4.5l-.5 7m3.75 0l-.5-7h4.5l-.5 7M9 15.75h6");
}

</style>
