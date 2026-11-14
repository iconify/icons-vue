<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bn8iivblo"/><path class="gzna7fybi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dig-site" /></template>
<style>
.bn8iivblo {
  d: path("M2.5 20c2.5-6 6-7.5 9.5-7.5s7 1.5 9.5 7.5Z");
}

.gzna7fybi {
  d: path("M10.25 12.75v-5.5A1.75 1.75 0 1 1 12 5.5a1.75 1.75 0 1 1 1.75 1.75v5.5M7 17.5h.01m9.99 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
