<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmgz4737p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:body-side" /></template>
<style>
.xmgz4737p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m1 4.5h2.25A1.75 1.75 0 0 1 15 11v4.5l-.75 4.5L17 21.5h-6.25l-.5-6L9.5 11A1.75 1.75 0 0 1 11 9.25m1.25 2.5V16");
}

</style>
