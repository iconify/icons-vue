<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mny18frqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chalk-bag" /></template>
<style>
.mny18frqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8h6c3.5 2.5 5 5.5 5 8c0 3.5-3 5.5-8 5.5s-8-2-8-5.5c0-2.5 1.5-5.5 5-8m-.432-.756L8 6.25A1.17 1.17 0 0 1 9.016 4.5h5.968A1.17 1.17 0 0 1 16 6.25l-.568.994A1.5 1.5 0 0 1 14.13 8H9.87a1.5 1.5 0 0 1-1.302-.756M10 4.5c0-2.75 4-2.75 4 0");
}

</style>
