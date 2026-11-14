<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g9ahx9bqo"/><path class="qehun0bnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-label-printer" /></template>
<style>
.g9ahx9bqo {
  d: path("M7 8V3.5h10V8M3 8h18v9H3Z");
}

.qehun0bnj {
  d: path("M7 14v6.5h7.5L17 18v-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
