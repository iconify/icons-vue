<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qqlv6qhkk"/><path class="htn_gwlxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biopsy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htn_gwlxh {
  fill: currentColor;
  d: path("M6.75 17.25za.48.48 0 0 1 .779.15l.096.225a.381.381 0 0 1-.5.5l-.225-.096a.48.48 0 0 1-.15-.779");
}

.qqlv6qhkk {
  d: path("m17.189 2.922l3.889 3.889a1.25 1.25 0 0 1 0 1.767a1.25 1.25 0 0 1-1.767 0l-3.889-3.889a1.25 1.25 0 0 1 0-1.767a1.25 1.25 0 0 1 1.767 0M16.5 7.5l-9.25 9.25M6 18l-2.5 2.5");
}

</style>
