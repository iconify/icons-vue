<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_ri-ub-a"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="zqzj48brb"/><path class="o3x_ulbmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hybrid-search-duotone-thin" /></template>
<style>
.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_ri-ub-a {
  fill: currentColor;
  d: path("m10 6 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.o3x_ulbmr {
  d: path("M7 14h6");
}

.zqzj48brb {
  d: path("m10 6 3 3 -3 3 -3 -3Z");
}

</style>
