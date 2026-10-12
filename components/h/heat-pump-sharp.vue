<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qer7occkz"/><circle class="to76gxjla"/><path class="srvysyb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heat-pump-sharp" /></template>
<style>
.qer7occkz {
  d: path("M2.75 3.75h18.5v14.5H2.75z");
}

.srvysyb_o {
  d: path("M9.25 11V8.25m0 2.75l2.4 1.4M9.25 11l-2.4 1.4m9.4-4.4v6m2.5-6v6m-12.5 4.25v3m11.5-3v3");
}

.to76gxjla {
  cx: 9.25px;
  cy: 11px;
  r: 4.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
