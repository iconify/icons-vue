<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="lnozolr0c"/><circle class="v257oxh1f"/><path class="ejow8ertj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drone-camera-sharp" /></template>
<style>
.ejow8ertj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17h.01");
}

.lnozolr0c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.5h5m8.5 0h5M8 8.75H5.25V4.5M16 8.75h2.75V4.5M8 6.75h8v5H8zm4 5v2.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v257oxh1f {
  cx: 12px;
  cy: 17px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
