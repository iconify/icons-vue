<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emtnhxbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-whole" /></template>
<style>
.emtnhxbpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12c2.5-4.5 6-6 9.5-6S18 9 18 12s-2 6-5.5 6s-7-1.5-9.5-6m15 0l3.5-3.5v7ZM7.5 11h.01");
}

</style>
