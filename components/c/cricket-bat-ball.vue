<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8gs7ym2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cricket-bat-ball" /></template>
<style>
.o8gs7ym2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.452 5.017l.531.531a2.625 2.625 0 0 1 0 3.712l-5.834 5.834a2.625 2.625 0 0 1-3.712 0l-.531-.531a2.625 2.625 0 0 1 0-3.712l5.834-5.834a2.625 2.625 0 0 1 3.712 0m-9.28 9.811l-3.89 3.89M3.5 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
