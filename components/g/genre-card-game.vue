<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="di77a2bmy"/><path class="xwkpn_bph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:genre-card-game" /></template>
<style>
.di77a2bmy {
  d: path("M13.125 6h3.75A2.625 2.625 0 0 1 19.5 8.625v9.75A2.625 2.625 0 0 1 16.875 21h-3.75a2.625 2.625 0 0 1-2.625-2.625v-9.75A2.625 2.625 0 0 1 13.125 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xwkpn_bph {
  d: path("M10.5 18L6.75 5.5L15 3l1 3M8.5 20L3 9l4-2.5m9 5.5l.445.668a1.5 1.5 0 0 1 0 1.664L16 15a1.202 1.202 0 0 1-2 0l-.445-.668a1.5 1.5 0 0 1 0-1.664L14 12a1.202 1.202 0 0 1 2 0");
}

</style>
