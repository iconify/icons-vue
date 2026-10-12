<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fhi1o5adk"/><circle class="sb4kn6-oq"/><path class="gjy7smbsp"/><path class="l63cci3ci"/><path class="bshrrcgek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:air-compressor-sharp" /></template>
<style>
.bshrrcgek {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 15.75v5");
}

.fhi1o5adk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.5h18.5v6.25H2.75z");
}

.gjy7smbsp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.75V9.5");
}

.l63cci3ci {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 19.5h.01");
}

.sb4kn6-oq {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
