<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="ceopgp_8f"/><path class="q6icwma0c"/><path class="gavuxkbkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:emergency-exit-sharp" /></template>
<style>
.ceopgp_8f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 18.25V6h3.75v12.25");
}

.gavuxkbkd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 9l-1.25 4.25m-2-2.5L9.5 9l2 2l1.5.25m-4.75 2l2.25 1.5v3m-2.25-4.5L6.5 17.5");
}

.q6icwma0c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ywno-sh7h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
