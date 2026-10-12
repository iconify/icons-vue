<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="c_1nltq2j"/><path class="u_3_acqhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alert-square-sharp" /></template>
<style>
.c_1nltq2j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.25v5.25");
}

.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u_3_acqhp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
