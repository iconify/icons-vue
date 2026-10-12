<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dyzch9b4x"/><circle class="eypmcvume"/><path class="j_sxo56nd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:content-credential-sharp" /></template>
<style>
.dyzch9b4x {
  d: path("M3.75 2.75h12.5v16.5H3.75zM7.25 7h5.5m-5.5 3.5h3.5");
}

.eypmcvume {
  cx: 16.5px;
  cy: 15px;
  r: 3.5px;
}

.j_sxo56nd {
  d: path("m15 15l1 1l2-2m-3 4.5v2.75l1.5-1l1.5 1V18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
