<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i8qt1xbzh"/><circle class="l0fn-57om"/><path class="ujy3-ns0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camera-sharp" /></template>
<style>
.i8qt1xbzh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9.25v-2h4.1l1.1-1.85l.433-.751l.867.001h4.5l.867-.001l.433.751l1.1 1.85h4.1v13H3.25v-2.5Z");
}

.l0fn-57om {
  cx: 12px;
  cy: 13.25px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ujy3-ns0y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 10.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
