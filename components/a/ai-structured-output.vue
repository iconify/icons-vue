<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik80hbc2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-structured-output" /></template>
<style>
.ik80hbc2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.5c-2 0-2 1-2 3v3C5.5 11 4.5 12 3 12c1.5 0 2.5 1 2.5 2.5v3c0 2 0 3 2 3m9-17c2 0 2 1 2 3v3c0 1.5 1 2.5 2.5 2.5c-1.5 0-2.5 1-2.5 2.5v3c0 2 0 3-2 3M9 8h6m-6 4h6m-6 4h6");
}

</style>
