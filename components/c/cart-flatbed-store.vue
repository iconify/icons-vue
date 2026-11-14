<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gm720zbjw"/><path class="wlfffupzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cart-flatbed-store" /></template>
<style>
.gm720zbjw {
  d: path("M4.5 15h15a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 16.5A1.5 1.5 0 0 1 4.5 15m2.25-7.5h6.5A1.75 1.75 0 0 1 15 9.25v4A1.75 1.75 0 0 1 13.25 15h-6.5A1.75 1.75 0 0 1 5 13.25v-4A1.75 1.75 0 0 1 6.75 7.5M19.5 15V4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wlfffupzx {
  d: path("M5 19.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m11 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
