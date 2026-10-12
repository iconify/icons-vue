<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="wisbhtbep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:life-buoy" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wisbhtbep {
  d: path("M12 8a4 4 0 1 0 0 8a4 4 0 1 0 0-8m2.75 1.25L18.5 5.5M9.25 9.25L5.5 5.5m3.75 9.25L5.5 18.5m9.25-3.75l3.75 3.75");
}

</style>
