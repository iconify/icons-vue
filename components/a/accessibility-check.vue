<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xe53owbmy"/><path class="jxivkumnb"/><path class="cylcq8lmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessibility-check" /></template>
<style>
.cylcq8lmg {
  d: path("M12 10.25V14l-3.25 6.25M12 14l3.25 6.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jxivkumnb {
  d: path("M4.75 9c4.85 1.35 9.65 1.35 14.5 0");
}

.xe53owbmy {
  cx: 12px;
  cy: 5px;
  r: 2px;
}

</style>
