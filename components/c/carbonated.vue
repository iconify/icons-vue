<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx5a2nbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carbonated" /></template>
<style>
.qx5a2nbea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 17.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m7-7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-4.25-5.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
