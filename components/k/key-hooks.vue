<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnvb9rbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:key-hooks" /></template>
<style>
.xnvb9rbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h18M6 4v3.5M12 4v4.5M18 4v3.5m-15 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 3v7m0-3h2.5m-2.5 3h2.5m6.5-10a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 3v7m0-3h2.5m-2.5 3h2.5");
}

</style>
