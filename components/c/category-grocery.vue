<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u3l783eav"/><path class="iqm7jubuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-grocery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iqm7jubuj {
  d: path("M6.75 11L3 6a2.5 2.5 0 0 1 4-3l6 8m1.75-.25V8.5C14.75 7 16 6.5 16 5V2.5h2.5V5c0 1.5 1.25 2 1.25 3.5v1.75M6 8l2.5-1M3.75 5l2.5-1");
}

.u3l783eav {
  d: path("m4 10l2 1.5L8 10l2 1.5l2-1.5l2 1.5l2-1.5l2 1.5l2-1.5v11.5H4Z");
}

</style>
