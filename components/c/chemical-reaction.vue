<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9tbcfb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chemical-reaction" /></template>
<style>
.z9tbcfb5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M3 16a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 3 16m6.75-4h4.5m-2-2l2 2l-2 2m5.25-6A1.75 1.75 0 1 0 21 8a1.75 1.75 0 1 0-3.5 0m-.5 7.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m2.25-6v3.75");
}

</style>
