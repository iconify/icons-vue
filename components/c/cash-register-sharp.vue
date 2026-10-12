<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="w0chgmb0q"/><path class="d_tf1xr4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cash-register-sharp" /></template>
<style>
.d_tf1xr4o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 11.5h.01m2.49 0h.01m2.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w0chgmb0q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.75h8V5H8zM12 5v3M7 8h11l.27.96l1.46 5.08l.27.96H4l.27-.96l1.46-5.08L6 8zm-4 7h18v5.25H3zm0 0h18m-11 2.6h4");
}

</style>
