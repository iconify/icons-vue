<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajh1kbcxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:insurance-chatbot" /></template>
<style>
.ajh1kbcxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9.5h13a1 1 0 0 1 1 1V19a1 1 0 0 1-1 1h-13a1 1 0 0 1-1-1v-8.5a1 1 0 0 1 1-1Zm6.5-7l2.25 1V5c0 1.25-1 2-2.25 2.5C10.75 7 9.75 6.25 9.75 5V3.5ZM9 13.75h.01m5.99 0h.01M10 17h4M2.5 13v3m19-3v3");
}

</style>
