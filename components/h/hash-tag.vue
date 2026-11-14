<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nry79ebih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hash-tag" /></template>
<style>
.nry79ebih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.9 10.32l2.813-3.375A2.63 2.63 0 0 1 8.729 6h10.146A2.625 2.625 0 0 1 21.5 8.625v6.75A2.625 2.625 0 0 1 18.875 18H8.729a2.63 2.63 0 0 1-2.016-.945L3.9 13.68a2.625 2.625 0 0 1 0-3.36M6.75 12h.01M13 8.75l-.75 6.5m4.5-6.5l-.75 6.5m-5.5-4.75h8m-8.25 3h8");
}

</style>
