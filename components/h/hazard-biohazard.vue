<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tn-e9xbej"/><circle class="dx6306lcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hazard-biohazard" /></template>
<style>
.dx6306lcu {
  cx: 12px;
  cy: 13.75px;
  r: 1.6px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tn-e9xbej {
  d: path("M14.17 4.9a2.5 2.5 0 1 1-4.34 0m8.75 15.15a2.5 2.5 0 1 1 2.17-3.75m-17.5 0a2.5 2.5 0 1 1 2.17 3.75");
}

</style>
