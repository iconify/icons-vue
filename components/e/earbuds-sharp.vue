<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="deritttri"/><circle class="vxis36bae"/><path class="j_r6_1buk"/><path class="u3wlq3b1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:earbuds-sharp" /></template>
<style>
.deritttri {
  cx: 7.25px;
  cy: 7.75px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_r6_1buk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 10.5v9.75m6-9.75v9.75");
}

.u3wlq3b1j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 7.25h.01m10.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vxis36bae {
  cx: 16.75px;
  cy: 7.75px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
