<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s8tiq70vk"/><path class="kwv9dtbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aromatherapy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwv9dtbon {
  d: path("M9.5 18.25c0-3 2-5 5-5c0 3-2 5-5 5");
}

.s8tiq70vk {
  d: path("M10.875 10h2.25a4.375 4.375 0 0 1 4.375 4.375v2.75a4.375 4.375 0 0 1-4.375 4.375h-2.25A4.375 4.375 0 0 1 6.5 17.125v-2.75A4.375 4.375 0 0 1 10.875 10M11 7h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 13 10h-2a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 11 7m-1 0V4.5a2 2 0 0 1 4 0V7");
}

</style>
