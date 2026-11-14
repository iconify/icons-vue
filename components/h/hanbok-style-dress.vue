<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0xghnbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hanbok-style-dress" /></template>
<style>
.i0xghnbao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3L12 6.5L15.5 3l4 2.5L18 9H6L4.5 5.5Zm-1 6C6 14 4 18 3.5 21h17c-.5-3-2.5-7-4-12m-3 0l.5 5.5");
}

</style>
