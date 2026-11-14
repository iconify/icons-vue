<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e96a1abai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bamboo-cutlery" /></template>
<style>
.e96a1abai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.5v5a2.5 2.5 0 0 0 5 0v-5m-2.5 0v19M10.5 6.75a3 4.25 0 1 0 6 0a3 4.25 0 1 0-6 0m3 4.25v10.5m3 0c0-4 1.5-5.5 5.5-5.5c0 4-1.5 5.5-5.5 5.5");
}

</style>
