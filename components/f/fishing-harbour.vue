<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jzc5m_ept"/><path class="aw9x48hsn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fishing-harbour" /></template>
<style>
.aw9x48hsn {
  d: path("M6.5 12h9L14 15H8Zm5 0V6.5l4 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzc5m_ept {
  d: path("M17.785 5.106a9 9 0 1 1-11.57 0");
}

</style>
