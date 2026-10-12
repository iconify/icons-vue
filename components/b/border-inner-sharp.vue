<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cim1a2bwc"/><path class="jddzqsu_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:border-inner-sharp" /></template>
<style>
.cim1a2bwc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h.01M3 7.5h.01m-.01 9h.01M3 21h.01M7.5 3h.01M7.5 21h.01M16.5 3h.01m-.01 18h.01M21 3h.01M21 7.5h.01m-.01 9h.01M21 21h.01");
}

.jddzqsu_d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v18m-9-9h18");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
