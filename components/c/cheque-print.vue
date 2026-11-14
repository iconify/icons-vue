<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-n46obft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheque-print" /></template>
<style>
.w-n46obft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6.5h12a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 11v-1A3.5 3.5 0 0 1 6 6.5m.5 0v-3a1 1 0 0 1 1-1h9a1 1 0 0 1 1 1v3m-12 8v6a1 1 0 0 0 1 1h11a1 1 0 0 0 1-1v-6m-10 3.25h4M18 10.5h.01");
}

</style>
