<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ets9m28xj"/><path class="ackg-fb3x"/><path class="kwkkx9b3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cling-wrap-box" /></template>
<style>
.ackg-fb3x {
  d: path("M9.5 12L16 9l5 1.5V17");
}

.ets9m28xj {
  d: path("M3 9h13v12H3zl1.5-6.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwkkx9b3h {
  d: path("M6.5 15a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 0h.01");
}

</style>
