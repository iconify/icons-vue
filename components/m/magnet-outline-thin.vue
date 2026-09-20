<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="thkmlu7qy"/><path class="coye-i88w"/><path class="i-58-pnpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:magnet-outline-thin" /></template>
<style>
.coye-i88w {
  d: path("M8 8v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-58-pnpd {
  d: path("M16 8v8");
}

.thkmlu7qy {
  d: path("M3 8h18v8H3Z");
}

</style>
