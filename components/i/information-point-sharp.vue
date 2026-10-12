<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="c32qe-lnv"/><path class="tsdqsjo2p"/><path class="l3j0385pd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:information-point-sharp" /></template>
<style>
.c32qe-lnv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75h15.5v11H4.25z");
}

.l3j0385pd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5v2.75m0 2.5v7.5m-3.5 0h7");
}

.tsdqsjo2p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
