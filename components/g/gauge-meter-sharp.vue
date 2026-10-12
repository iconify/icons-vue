<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u4e3r2b2q"/><path class="s8tk7gw-f"/><circle class="vtw09psrf"/><path class="nz62cmbrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gauge-meter-sharp" /></template>
<style>
.nz62cmbrj {
  d: path("m12.86 15.02l1.58-2.25");
}

.s8tk7gw-f {
  d: path("M5.25 16.25a6.75 6.75 0 0 1 13.5 0");
}

.u4e3r2b2q {
  d: path("M2.75 16.25a9.25 9.25 0 0 1 18.5 0v4.25H2.75v-2Z");
}

.vtw09psrf {
  cx: 12px;
  cy: 16.25px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
