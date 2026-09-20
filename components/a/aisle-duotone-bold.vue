<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z6qs6gbnt"/><path class="fmbgtccaf"/><path class="u3-ft-2ah"/><path class="w0g1t34ku"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="qxpc-f42y"/><path class="f5e6x3ddq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:aisle-duotone-bold" /></template>
<style>
.f5e6x3ddq {
  d: path("M14.5 12v7");
}

.fmbgtccaf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qxpc-f42y {
  d: path("M9.5 12v7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tp7101bon {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

.u3-ft-2ah {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w0g1t34ku {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yb0d-pkkp {
  d: path("M4 8v14h16V8");
}

.z6qs6gbnt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
