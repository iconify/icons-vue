<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yl82r_g1r"/><circle class="snuqc64bb"/><path class="ffi_0xbjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-plane-sharp" /></template>
<style>
.ffi_0xbjf {
  d: path("m16.25 14l-.75-4.5l-.286-2.268l2.286.018h3V14m-10.25 2.5l2-7");
}

.snuqc64bb {
  cx: 5.75px;
  cy: 12px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yl82r_g1r {
  d: path("M2.75 14h18.5v5.5H2.75z");
}

</style>
