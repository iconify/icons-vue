<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="v96e9zbxw"/><path class="pl7gqzo0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:encryption-key-sharp" /></template>
<style>
.pl7gqzo0w {
  d: path("M7.5 12v-2m0 2v2m0-2l1.73-1M7.5 12l-1.73 1m1.73-1l1.73 1M7.5 12l-1.73-1m6.48 1h9M19 12v3.25M16 12v2.5");
}

.v96e9zbxw {
  cx: 7.5px;
  cy: 12px;
  r: 4.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
