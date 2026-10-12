<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="f_362pbxn"/><path class="zt7gkkpde"/><circle class="lf940mbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crosshair" /></template>
<style>
.f_362pbxn {
  cx: 12px;
  cy: 12px;
  r: 7px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lf940mbnz {
  cx: 12px;
  cy: 12px;
  r: 1.25px;
}

.zt7gkkpde {
  d: path("M12 2.75v5.5m0 7.5v5.5M2.75 12h5.5m7.5 0h5.5");
}

</style>
