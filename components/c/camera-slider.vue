<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="we11yudsz"/><path class="kc6v2sp7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-slider" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kc6v2sp7z {
  d: path("M10.5 7.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M7 18.5h10M15.5 17l1.5 1.5l-1.5 1.5");
}

.we11yudsz {
  d: path("M9.625 3h4.75A2.625 2.625 0 0 1 17 5.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 7 8.875v-3.25A2.625 2.625 0 0 1 9.625 3M12 11.5v3m-9.5 0h19");
}

</style>
