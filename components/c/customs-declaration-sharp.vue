<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="elmqikbxd"/><circle class="em9cvctqt"/><path class="ux464eb-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:customs-declaration-sharp" /></template>
<style>
.elmqikbxd {
  d: path("M3.75 2.75h16.5v18.5H3.75zM7 6h10M7 9.5h6");
}

.em9cvctqt {
  cx: 12px;
  cy: 15px;
  r: 3.25px;
}

.ux464eb-x {
  d: path("M8.75 15h6.5M12 11.75a6.5 6.5 0 0 0 0 6.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
