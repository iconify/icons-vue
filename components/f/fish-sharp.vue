<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="d50wu26-f"/><path class="fmt7gtbnv"/><path class="hdt5r7dnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fish-sharp" /></template>
<style>
.d50wu26-f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12c2-3.5 5-5.25 8-5.25S20.25 9.5 21.25 12c-1 2.5-2.75 5.25-5.75 5.25s-6-1.75-8-5.25Zm-1 0L3.75 8.75l-.907-.818L2.75 9.15v5.7l.093 1.218l.907-.818Z");
}

.fmt7gtbnv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 11h.01");
}

.hdt5r7dnn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 9.25L14.429 12l-1.179 2.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
