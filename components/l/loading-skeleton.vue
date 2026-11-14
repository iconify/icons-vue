<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is5radb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loading-skeleton" /></template>
<style>
.is5radb8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 3.5h.75A2.625 2.625 0 0 1 9.5 6.125v.75A2.625 2.625 0 0 1 6.875 9.5h-.75A2.625 2.625 0 0 1 3.5 6.875v-.75A2.625 2.625 0 0 1 6.125 3.5M13 5h7.5M13 8.5h4.5M3.5 14h17m-17 5H14");
}

</style>
