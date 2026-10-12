<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="shvec_xgt"/><circle class="ons53cb4g"/><path class="b9fbe6bhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:locate-off-sharp" /></template>
<style>
.b9fbe6bhi {
  d: path("M12 2.75V5.5m0 13v2.75M2.75 12H5.5m13 0h2.75");
}

.ons53cb4g {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

.shvec_xgt {
  cx: 12px;
  cy: 12px;
  r: 6.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
