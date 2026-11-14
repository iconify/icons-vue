<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w72t88byv"/><path class="xnks3i1ka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:block-search" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w72t88byv {
  d: path("m13.075 20.899l-.221.124q-.097.054-.201.096t-.212.07t-.219.042q-.11.015-.222.015t-.222-.015q-.111-.014-.219-.042t-.212-.07t-.201-.096l-6.75-3.772q-.101-.057-.195-.126q-.093-.07-.176-.151q-.083-.082-.154-.173q-.072-.092-.131-.192q-.058-.101-.103-.208t-.076-.219t-.046-.228t-.015-.231V8.277q0-.116.015-.231q.016-.116.046-.228q.031-.112.076-.219t.103-.208q.059-.1.131-.192q.071-.091.154-.173t.176-.151q.094-.069.195-.126l6.75-3.772q.097-.054.201-.096t.212-.07t.219-.042q.11-.015.222-.015t.222.015q.111.014.219.042t.212.07t.201.096l6.75 3.772q.101.057.195.126q.093.07.176.151q.083.082.154.173q.072.092.131.192q.058.101.103.208t.076.219t.046.228t.015.231v4.496");
}

.xnks3i1ka {
  d: path("M3.5 7.25L12 12l8.5-4.75M12 12v3.5m0 3.5v2.5m2.5-4.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m4.75 2l2 2");
}

</style>
