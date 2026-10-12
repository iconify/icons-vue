<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ouliy2hpj"/><path class="t7je_8b6s"/><path class="uf-sov_ty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:game-over-sharp" /></template>
<style>
.ouliy2hpj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4h18.5v13.5H2.75z");
}

.t7je_8b6s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 9.25h.01m6.99 0h.01");
}

.uf-sov_ty {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 14.5a3.5 3.5 0 0 1 6 0m-3 3v3.75m-3.5 0h7");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
