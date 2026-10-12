<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hcf090boh"/><path class="zp4s8wb4p"/><path class="bjzryejvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:license-plate-sharp" /></template>
<style>
.bjzryejvl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 13.75h4.25m3 0h4.25");
}

.hcf090boh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h18.5v11.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zp4s8wb4p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 9.25h.01m11.49 0h.01");
}

</style>
