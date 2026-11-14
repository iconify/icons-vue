<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeepaccui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eyebrow-gel" /></template>
<style>
.oeepaccui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 6za2.5 2.5 0 0 1 2.5 2.5V19a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1-2.5-2.5V8.5A2.5 2.5 0 0 1 17 6M6.75 15h1.5A1.75 1.75 0 0 1 10 16.75v3a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 5 19.75v-3A1.75 1.75 0 0 1 6.75 15m.75 0v-3.5l-2.25-1.25l4.5-1.5l-4.5-1.5l4.5-1.5l-4.5-1.5L7.5 3");
}

</style>
