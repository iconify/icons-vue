<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h4rx44bnm"/><path class="brmmdbeqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:commercial-property" /></template>
<style>
.brmmdbeqt {
  d: path("M10 12.5h4a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 19v-5a1.5 1.5 0 0 1 1.5-1.5");
}

.h4rx44bnm {
  d: path("M6.625 8h10.75A2.625 2.625 0 0 1 20 10.625v7.25a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 17.875v-7.25A2.625 2.625 0 0 1 6.625 8M3 8l2-4h14l2 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
