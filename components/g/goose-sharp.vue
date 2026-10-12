<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="r768hbcyy"/><path class="e877b1mud"/><path class="a2mhuibjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:goose-sharp" /></template>
<style>
.a2mhuibjy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 5.5h.01");
}

.e877b1mud {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.4 5L2.75 6.1L5.5 7Zm6.6 9l2.64 1.886l3.86-.386m-7.5 4v1.75m3-1.75v1.75");
}

.r768hbcyy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 5.75V3h5.5v7.5L18 11.75c1.75.3 3 1.75 3 3.5c0 2.5-2.25 4.25-5 4.25h-4.25c-3 0-4.75-2.25-4.75-5v-1.833L8.25 11V8.5h-3z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
