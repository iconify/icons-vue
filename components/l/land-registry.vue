<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ibdmb-bqs"/><path class="p2ykqj2qu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:land-registry" /></template>
<style>
.ibdmb-bqs {
  d: path("M4.5 19.25V5A2.5 2.5 0 0 1 7 2.5h12.5V17H6.75a2.25 2.25 0 0 0 0 4.5H19.5");
}

.p2ykqj2qu {
  d: path("M8 6.75V5h1.75m4.5 0H16v1.75m0 4.5V13h-1.75m-4.5 0H8v-1.75m2.25-.25V7m0 0l3.25 1l-3.25 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
