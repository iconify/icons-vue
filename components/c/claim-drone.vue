<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-rkurqhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:claim-drone" /></template>
<style>
.k-rkurqhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 10.5h2a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2a2 2 0 0 1 2-2M9 11L5 8m10 3l4-3M3 7h4m10 0h4M10.5 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
