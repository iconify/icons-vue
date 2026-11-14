<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nr9-s_bgw"/><path class="fag3z6byk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basketball-court-top" /></template>
<style>
.fag3z6byk {
  d: path("M9.25 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M4 9h1a1.5 1.5 0 0 1 1.5 1.5v3A1.5 1.5 0 0 1 5 15H4a1.5 1.5 0 0 1-1.5-1.5v-3A1.5 1.5 0 0 1 4 9m15 0h1a1.5 1.5 0 0 1 1.5 1.5v3A1.5 1.5 0 0 1 20 15h-1a1.5 1.5 0 0 1-1.5-1.5v-3A1.5 1.5 0 0 1 19 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr9-s_bgw {
  d: path("M5.125 5.5h13.75A2.625 2.625 0 0 1 21.5 8.125v7.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 15.875v-7.75A2.625 2.625 0 0 1 5.125 5.5M12 5.5v13");
}

</style>
