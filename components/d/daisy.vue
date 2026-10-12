<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pszwkb-my"/><circle class="gp0egaclj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:daisy" /></template>
<style>
.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pszwkb-my {
  d: path("M9.85 3.97a2.5 2.5 0 0 1 4.3 0a2.5 2.5 0 0 1 3.72 2.16a2.5 2.5 0 0 1 2.16 3.72a2.5 2.5 0 0 1 0 4.3a2.5 2.5 0 0 1-2.16 3.72a2.5 2.5 0 0 1-3.72 2.16a2.5 2.5 0 0 1-4.3 0a2.5 2.5 0 0 1-3.72-2.16a2.5 2.5 0 0 1-2.16-3.72a2.5 2.5 0 0 1 0-4.3a2.5 2.5 0 0 1 2.16-3.72a2.5 2.5 0 0 1 3.72-2.16");
}

</style>
