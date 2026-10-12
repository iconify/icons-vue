<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><circle class="b405utblj"/><circle class="fkwkb8hzx"/><path class="pld_2hbet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fire-hose-sharp" /></template>
<style>
.b405utblj {
  cx: 10.5px;
  cy: 11px;
  r: 4.5px;
}

.fkwkb8hzx {
  cx: 10.5px;
  cy: 11px;
  r: 1.5px;
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.pld_2hbet {
  d: path("M10.5 15.5h6.25L18 17");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
