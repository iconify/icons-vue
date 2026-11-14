<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r677kdbay"/><path class="naca-ibqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cocktail-cabinet" /></template>
<style>
.naca-ibqe {
  d: path("M9.5 8h5L12 11Zm2.5 3v3.5");
}

.r677kdbay {
  d: path("M6.5 4.5h11v15h-11Zm0 0L3 6.5v11l3.5 2Zm11 0l3.5 2v11l-3.5 2Zm-11 10h11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
