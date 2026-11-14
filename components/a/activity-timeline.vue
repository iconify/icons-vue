<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjkzx_bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:activity-timeline" /></template>
<style>
.hjkzx_bjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-12v3m0 4v3m4-12h4.5m-17 7H8m8 7h3.5");
}

</style>
