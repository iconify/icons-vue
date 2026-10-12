<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rn2syz-tm"/><circle class="v3bfe6lup"/><path class="kaq3ynbxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barre-sharp" /></template>
<style>
.kaq3ynbxn {
  d: path("M14.5 7.5v13.75m0-7.75l6.25-3.25m-6.25-1.5l-4.25 1.5m4.25-1.5l4.25-2.5");
}

.rn2syz-tm {
  d: path("M2.75 10.25h7.5m-5.5 0v11");
}

.v3bfe6lup {
  cx: 14.5px;
  cy: 4.75px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
