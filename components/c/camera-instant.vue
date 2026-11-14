<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yqo3u418p"/><path class="wtbn30bgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-instant" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wtbn30bgg {
  d: path("M9 8.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m8-3h.01M5.5 19h13");
}

.yqo3u418p {
  d: path("M7.375 2.5h9.25A4.375 4.375 0 0 1 21 6.875v3.75A4.375 4.375 0 0 1 16.625 15h-9.25A4.375 4.375 0 0 1 3 10.625v-3.75A4.375 4.375 0 0 1 7.375 2.5M5.5 15v7h13v-7");
}

</style>
