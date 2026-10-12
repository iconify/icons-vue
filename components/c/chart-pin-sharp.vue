<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hx11cvbsv"/><path class="mqc8npzbg"/><path class="o6a500beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-pin-sharp" /></template>
<style>
.hx11cvbsv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.75v16.5h16.5");
}

.mqc8npzbg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.75 17.25l5.25-3L15 16l5-4.5m-8-8.75A3.25 3.25 0 0 0 8.75 6c0 2.25 3.25 4.75 3.25 4.75s3.25-2.5 3.25-4.75A3.25 3.25 0 0 0 12 2.75Z");
}

.o6a500beq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
