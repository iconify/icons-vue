<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uhwk2grtx"/><path class="yo0f25b1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grill-pan" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uhwk2grtx {
  width: 12.5px;
  height: 12.5px;
  x: 2.75px;
  y: 6px;
  rx: 2.5px;
}

.yo0f25b1l {
  d: path("M6 9.25v6m3-6v6m3-6v6m3.25-6l5.5-5.5");
}

</style>
