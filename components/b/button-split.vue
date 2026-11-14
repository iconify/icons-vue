<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="htuf028kj"/><path class="p47ibdq9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:button-split" /></template>
<style>
.htuf028kj {
  d: path("M2.5 6h19v12h-19Zm11 0v12M6 12h4.5");
}

.p47ibdq9c {
  d: path("m16 11l1.5 1.5L19 11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
