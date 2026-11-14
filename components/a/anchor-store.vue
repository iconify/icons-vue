<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mwwwzccsm"/><path class="n9bggrbwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anchor-store" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mwwwzccsm {
  d: path("M5.5 14V2.5h13V14M3 16.75L4.5 14h15l1.5 2.75m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0");
}

.n9bggrbwy {
  d: path("M9.5 5h.5a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-.5a1 1 0 0 1-1-1a1 1 0 0 1 1-1M14 5h.5a1 1 0 0 1 1 1a1 1 0 0 1-1 1H14a1 1 0 0 1-1-1a1 1 0 0 1 1-1M9.5 9.25h.5a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-.5a1 1 0 0 1-1-1a1 1 0 0 1 1-1m4.5 0h.5a1 1 0 0 1 1 1a1 1 0 0 1-1 1H14a1 1 0 0 1-1-1a1 1 0 0 1 1-1M5.5 21.5h13");
}

</style>
