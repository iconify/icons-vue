<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rh4excbyl"/><path class="mpgqjz4wc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheque-amount-words" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mpgqjz4wc {
  d: path("M4.75 15L6.5 9l1.75 6M5.5 13h2m3.25-4v6m0-1.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m9.237 1.237a1.75 1.75 0 1 1 0-2.474");
}

.rh4excbyl {
  d: path("M6 5.5h12A3.5 3.5 0 0 1 21.5 9v6a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 15V9A3.5 3.5 0 0 1 6 5.5");
}

</style>
