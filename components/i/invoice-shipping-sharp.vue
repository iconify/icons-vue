<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o6vmj6amn"/><path class="ie4w_pbnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:invoice-shipping-sharp" /></template>
<style>
.ie4w_pbnp {
  d: path("M9 12.5h6v5H9zm3 0v1.75");
}

.o6vmj6amn {
  d: path("M5 3.75v-1h14v18.5l-2.33-1.5l-2.34 1.5l-2.33-1.5l-2.33 1.5l-2.34-1.5L5 21.25Zm3 3h8m-8 3h5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
