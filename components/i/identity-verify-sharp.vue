<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bicgcfb5m"/><circle class="j19le_uky"/><path class="sjadambmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:identity-verify-sharp" /></template>
<style>
.bicgcfb5m {
  d: path("M2.75 5.75h18.5v12.5H2.75z");
}

.j19le_uky {
  cx: 8px;
  cy: 10.25px;
  r: 2px;
}

.sjadambmn {
  d: path("M4.75 18.25a3.25 3.25 0 0 1 6.5 0M14 13.5l1.75 1.75l3.25-3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
