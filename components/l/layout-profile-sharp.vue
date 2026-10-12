<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ohxdrbbbi"/><circle class="d4r-zbeif"/><path class="f_h0hcbib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layout-profile-sharp" /></template>
<style>
.d4r-zbeif {
  cx: 12px;
  cy: 8px;
  r: 2.25px;
}

.f_h0hcbib {
  d: path("m8 15l1.2-2.25h5.6L16 15m-8 3.25h8");
}

.ohxdrbbbi {
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
