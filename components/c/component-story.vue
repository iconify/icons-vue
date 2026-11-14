<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="px-uyh2ye"/><path class="up54fvb6t"/><path class="lnt5y-b4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:component-story" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lnt5y-b4x {
  fill: currentColor;
  d: path("M13 5.75za1.06 1.06 0 0 1 0 1.5a1.06 1.06 0 0 1-1.5 0a1.06 1.06 0 0 1 0-1.5a1.06 1.06 0 0 1 1.5 0m0 6za1.06 1.06 0 0 1 0 1.5a1.06 1.06 0 0 1-1.5 0a1.06 1.06 0 0 1 0-1.5a1.06 1.06 0 0 1 1.5 0m-3-3za1.06 1.06 0 0 1 0 1.5a1.06 1.06 0 0 1-1.5 0a1.06 1.06 0 0 1 0-1.5a1.06 1.06 0 0 1 1.5 0m6 0za1.06 1.06 0 0 1 0 1.5a1.06 1.06 0 0 1-1.5 0a1.06 1.06 0 0 1 0-1.5a1.06 1.06 0 0 1 1.5 0");
}

.px-uyh2ye {
  d: path("M5 19V5a2.5 2.5 0 0 1 2.5-2.5h12v19h-12A2.5 2.5 0 0 1 5 19");
}

.up54fvb6t {
  d: path("M5 19a2.5 2.5 0 0 1 2.5-2.5h12");
}

</style>
