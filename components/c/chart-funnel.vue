<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr7wv3izz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-funnel" /></template>
<style>
.tr7wv3izz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.788 4h10.424a2.625 2.625 0 0 1 2.458 3.547l-4.031 10.75A2.625 2.625 0 0 1 13.181 20h-2.362a2.625 2.625 0 0 1-2.458-1.703L4.33 7.547A2.625 2.625 0 0 1 6.788 4M5 9.5h14M7 14.75h10");
}

</style>
