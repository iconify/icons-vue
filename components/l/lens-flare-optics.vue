<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wgzp02b-e"/><path class="ezlaigbou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lens-flare-optics" /></template>
<style>
.ezlaigbou {
  d: path("M6 14.5A3.5 3.5 0 0 1 9.5 11m7-3.5l3-3M19 12l2.5-.75M12 5l.75-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wgzp02b-e {
  d: path("M2.5 14.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>
