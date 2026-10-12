<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dnr2q8hlr"/><circle class="r2akiquzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:headlight-sharp" /></template>
<style>
.dnr2q8hlr {
  d: path("m4.48 7.29l11.04-1.58L17 5.5l1.23.87l1.79 1.26l1.23.87v8.25l-1.5.08l-15.25.84l-1.5.08V7.5zM14.5 7v9");
}

.r2akiquzi {
  cx: 9px;
  cy: 12px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
