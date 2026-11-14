<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8fnszv9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leak-detector" /></template>
<style>
.s8fnszv9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5h19M2.5 13h19M11.125 3h1.75A2.625 2.625 0 0 1 15.5 5.625v.25A2.625 2.625 0 0 1 12.875 8.5h-1.75A2.625 2.625 0 0 1 8.5 5.875v-.25A2.625 2.625 0 0 1 11.125 3M11 10.75l1.5 1l-1 1.25m.5 3l1.5 1.75a2.25 2.25 0 1 1-3 0Z");
}

</style>
