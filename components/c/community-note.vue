<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cp-1d2tbx"/><path class="nodwwzb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:community-note" /></template>
<style>
.cp-1d2tbx {
  d: path("M2.5 6.5a2 2 0 0 1 2-2H16l5.5 5.5v7.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nodwwzb4z {
  d: path("M16 4.5V10h5.5M6 9h6.5M6 12.75h12M6 16.5h8");
}

</style>
