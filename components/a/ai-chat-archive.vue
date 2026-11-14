<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohtsctbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-chat-archive" /></template>
<style>
.ohtsctbmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3H17a2.5 2.5 0 0 1 2.5 2.5v5A2.5 2.5 0 0 1 17 13h-6.5l-4 3.5V13h-1A2.5 2.5 0 0 1 3 10.5v-5A2.5 2.5 0 0 1 5.5 3m10.625 13h4.25a1.125 1.125 0 0 1 1.125 1.125a1.125 1.125 0 0 1-1.125 1.125h-4.25A1.125 1.125 0 0 1 15 17.125A1.125 1.125 0 0 1 16.125 16m-.375 2.25v2.25a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1v-2.25");
}

</style>
