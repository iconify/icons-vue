<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2wsm_bqo"/><path class="pn09qjb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:art-label" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p2wsm_bqo {
  d: path("M8.5 5H19a2.5 2.5 0 0 1 2.5 2.5v9A2.5 2.5 0 0 1 19 19H8.5l-6-7Z");
}

.pn09qjb-c {
  d: path("M6.75 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.75-2H18m-5.5 4H16");
}

</style>
