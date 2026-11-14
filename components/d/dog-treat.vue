<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roa06wb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-treat" /></template>
<style>
.roa06wb7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 10h9a2.25 2.25 0 1 1 3 2a2.25 2.25 0 1 1-3 2h-9a2.25 2.25 0 1 1-3-2a2.25 2.25 0 1 1 3-2m3 2h.01m2.99 0h.01");
}

</style>
