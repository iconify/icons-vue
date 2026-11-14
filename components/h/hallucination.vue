<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lokzv5bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hallucination" /></template>
<style>
.lokzv5bwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 20.5v-10a6.5 6.5 0 0 1 13 0v10l-2.5-2l-2 2l-2-2l-2 2l-2-2Zm4-9.5h.01m4.99 0h.01");
}

</style>
