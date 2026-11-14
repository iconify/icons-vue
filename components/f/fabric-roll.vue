<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lcg02sl1z"/><path class="w5ki9bcgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fabric-roll" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lcg02sl1z {
  d: path("M2.5 10a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.w5ki9bcgq {
  d: path("M9 16.5h11a1.5 1.5 0 0 1 1.5 1.5v2.5M7 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
