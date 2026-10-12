<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jx0p6s4hi"/><circle class="ddy7nc0xh"/><path class="ilas_nbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:demolition-ball-sharp" /></template>
<style>
.ddy7nc0xh {
  cx: 8.25px;
  cy: 15.25px;
  r: 3px;
}

.ilas_nbty {
  d: path("M14.25 9.25h7v12h-7zm0 4h7m-7 4h7");
}

.jx0p6s4hi {
  d: path("M2.75 6.5L5.5 3.25h2.75v9");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
