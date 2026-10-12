<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="si-3lcc7i"/><circle class="optez1bab"/><path class="vxp1gibff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:action-camera-sharp" /></template>
<style>
.optez1bab {
  cx: 14.5px;
  cy: 13px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.si-3lcc7i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.75h18.5v12.5H2.75zm3 0v-2.5h3.5v2.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vxp1gibff {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 10.5h.01");
}

</style>
