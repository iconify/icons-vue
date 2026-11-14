<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ct-ahl7uc"/><path class="wbnftuf_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grafting-knife" /></template>
<style>
.ct-ahl7uc {
  d: path("m9 12.5l-6 6A1.75 1.75 0 0 0 5.5 21l6-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbnftuf_j {
  d: path("M9 12.5L17.5 4c1.5-1.5 4-1 3.5 1.5c-1 4.5-5 8-9.5 9.5Z");
}

</style>
