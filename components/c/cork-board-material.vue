<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h8zm1elku"/><path class="vvuwsmbdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cork-board-material" /></template>
<style>
.h8zm1elku {
  d: path("M7.375 4h9.25A4.375 4.375 0 0 1 21 8.375v8.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-8.25A4.375 4.375 0 0 1 7.375 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vvuwsmbdi {
  d: path("M9.5 7h5l-1 3l1.5 2H9l1.5-2Zm2.5 5v3.5m-5 2h.01M17 17h.01");
}

</style>
