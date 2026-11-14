<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo25fgbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dns-filter" /></template>
<style>
.qo25fgbhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h18v7.5H3Zm11.4 18H3v-7.5h7.1M6.5 6.75h.01m-.01 10.5h.01M14.75 15h6.75L19 18.25v3.25l-1.75-1v-2.25Z");
}

</style>
