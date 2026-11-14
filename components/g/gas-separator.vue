<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntb57hhim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gas-separator" /></template>
<style>
.ntb57hhim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 5.5zA3.5 3.5 0 0 1 14.5 9v6a3.5 3.5 0 0 1-3.5 3.5A3.5 3.5 0 0 1 7.5 15V9A3.5 3.5 0 0 1 11 5.5m0 0v-3h6m-6 16v3h6M7.5 14h7");
}

</style>
