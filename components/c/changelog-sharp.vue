<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="v2fwifbsf"/><path class="nbi0lcc_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:changelog-sharp" /></template>
<style>
.nbi0lcc_d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 12h.01m-.01 4h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v2fwifbsf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h16.5v18.5H3.75zm4 4v2.5M6.5 8H9m2.75 0h4.5m-4.5 4h4.5m-4.5 4h2.5");
}

</style>
