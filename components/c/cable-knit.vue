<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k57xcbcoz"/><path class="en_o_wbfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-knit" /></template>
<style>
.en_o_wbfu {
  d: path("M15 2.5C15 7 9 7 9 12s6 5 6 9.5M5 2.5v19m14-19v19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k57xcbcoz {
  d: path("M9 2.5C9 7 15 7 15 12s-6 5-6 9.5");
}

</style>
