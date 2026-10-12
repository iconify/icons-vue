<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="w47qa_byy"/><circle class="ld7nlxb7r"/><path class="chzhupbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drum-kit-sharp" /></template>
<style>
.chzhupbxz {
  d: path("M4.25 2.75h6.5v3.5h-6.5zm14.5 3v15.5m-2.5-15.5h5");
}

.ld7nlxb7r {
  cx: 10px;
  cy: 15.25px;
  r: 2.5px;
}

.w47qa_byy {
  cx: 10px;
  cy: 15.25px;
  r: 6px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
