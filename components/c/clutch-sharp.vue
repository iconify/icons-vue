<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f_qzn2nco"/><path class="e3i6g-b2g"/><circle class="n3qax8-nt"/><path class="f8gwd2bht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clutch-sharp" /></template>
<style>
.e3i6g-b2g {
  d: path("M3.25 9.75q3.75 2.85 7.5 3m2.5 0q3.75-.15 7.5-3");
}

.f_qzn2nco {
  d: path("M2.75 8.5h18.5v9H2.75z");
}

.f8gwd2bht {
  d: path("M5.5 17.5C3.75 19 4 21.25 6 21.25s2.25-2 1.25-3.75");
}

.n3qax8-nt {
  cx: 12px;
  cy: 12.75px;
  r: 1.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
