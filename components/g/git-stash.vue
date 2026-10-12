<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lgf9habjn"/><path class="z4gavt2hv"/><circle class="q1fvssb8e"/><path class="vag9hybes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-stash" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgf9habjn {
  width: 16.5px;
  height: 8.5px;
  x: 3.75px;
  y: 12.75px;
  rx: 2.25px;
}

.q1fvssb8e {
  cx: 12px;
  cy: 6.5px;
  r: 2.25px;
}

.vag9hybes {
  d: path("M12 2.75v1.5m0 4.5v2");
}

.z4gavt2hv {
  d: path("M3.75 16h4.5l1.25 1.75h5L15.75 16h4.5");
}

</style>
