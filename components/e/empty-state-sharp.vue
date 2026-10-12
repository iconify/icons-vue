<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l7yfq-b6e"/><path class="uwqhzccap"/><path class="pn5jvzxfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:empty-state-sharp" /></template>
<style>
.l7yfq-b6e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.pn5jvzxfw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 17h5");
}

.uwqhzccap {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 6.5h.01m3.49 0h.01m3.49 0h.01M15.5 10h.01m-.01 3.5h.01m-3.51 0h.01m-3.51 0h.01M8.5 10h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
