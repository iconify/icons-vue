<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kdgv2bbhr"/><path class="kxeil3b5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:board-game-family" /></template>
<style>
.kdgv2bbhr {
  d: path("M11.2 20.5H2.5v-18h18v8.7m-12-8.7v18m6-18v8.7m-12-2.7h18m-18 6h8.7m-5.7-3h.01m5.99-6h.01");
}

.kxeil3b5a {
  d: path("M14 14h7v7h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
