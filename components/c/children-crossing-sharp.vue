<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="q6icwma0c"/><path class="jphca-btc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:children-crossing-sharp" /></template>
<style>
.jphca-btc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 8.75l-.5 4l-2 4m2-4l2.5 1.5v3m-4.75-6.5l2.75-2l2.5 1.5m1.75 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
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
