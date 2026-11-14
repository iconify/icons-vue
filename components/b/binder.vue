<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ek_q-xb8w"/><path class="uq9511bvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:binder" /></template>
<style>
.ek_q-xb8w {
  d: path("M6.25 2.5h14v19h-14Zm-2.5 4H8.5M3.75 12H8.5m-4.75 5.5H8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uq9511bvr {
  d: path("M11.25 6h6v4h-6Z");
}

</style>
