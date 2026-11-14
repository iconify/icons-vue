<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m51etslkz"/><path class="bdgoctbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donate-car" /></template>
<style>
.bdgoctbfy {
  d: path("M4 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6.5 9.75l-2.5-2.5a1.77 1.77 0 0 1 2.5-2.5a1.77 1.77 0 0 1 2.5 2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m51etslkz {
  d: path("M4 12H2.5V9c0-.75.5-1.25 1.25-1.5L5.5 7l2-3.5h5L15 7l1.25.25c.75.25 1.25.75 1.25 1.5V12H16m-4 0H8");
}

</style>
