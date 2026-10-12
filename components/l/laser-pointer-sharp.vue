<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="asl7bkfix"/><path class="su7wuov-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laser-pointer-sharp" /></template>
<style>
.asl7bkfix {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.1 20.1l-1.2-1.2l-1.06-1.06l1.06-1.06l4.88-4.88l1.06-1.06l1.06 1.06l1.2 1.2l1.06 1.06l-1.06 1.06l-4.88 4.88l-1.06 1.06zm1.4-2.6l2-2m5.25-5.25L16.5 7.5");
}

.su7wuov-l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 5.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
