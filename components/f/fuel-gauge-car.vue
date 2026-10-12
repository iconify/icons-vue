<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g0mhe_b-x"/><circle class="zur2nlbbt"/><path class="t8fk3eyax"/><rect class="laz2awmxp"/><path class="vto9-1hou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-gauge-car" /></template>
<style>
.g0mhe_b-x {
  d: path("m6.15 14.88l-1.29.75a8.25 8.25 0 1 1 14.28 0l-1.29-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.laz2awmxp {
  width: 4px;
  height: 5px;
  x: 8.5px;
  y: 16.25px;
  rx: 0.75px;
}

.t8fk3eyax {
  d: path("m10.79 11.18l-4.34-1.17");
}

.vto9-1hou {
  d: path("M12.5 17.5h2.25a.75.75 0 0 1 .75.75v2.5");
}

.zur2nlbbt {
  cx: 12px;
  cy: 11.5px;
  r: 1.25px;
}

</style>
