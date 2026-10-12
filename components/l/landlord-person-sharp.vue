<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="vqgavtc7j"/><path class="trwu8yb8i"/><path class="y_atc20_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:landlord-person-sharp" /></template>
<style>
.trwu8yb8i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V15.5h11v5.75Zm14-.75V14l.53-.53l1.19-1.19l.53-.53l.53.53l1.19 1.19l.53.53v7.25h-4.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vqgavtc7j {
  cx: 8.25px;
  cy: 7.25px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_atc20_f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 17.25h.01");
}

</style>
