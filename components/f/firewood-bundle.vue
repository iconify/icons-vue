<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tx83_10xb"/><path class="uiomocbol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:firewood-bundle" /></template>
<style>
.tx83_10xb {
  d: path("M3 15.75a4.5 4.5 0 1 1 9 0a4.5 4.5 0 1 1-9 0Zm3.5 0a1 1 0 1 1 2 0a1 1 0 1 1-2 0Zm5.5 0a4.5 4.5 0 1 1 9 0a4.5 4.5 0 1 1-9 0Zm3.5 0a1 1 0 1 1 2 0a1 1 0 1 1-2 0Z");
}

.uiomocbol {
  d: path("M7.5 8a4.5 4.5 0 1 1 9 0a4.5 4.5 0 1 1-9 0ZM11 8a1 1 0 1 1 2 0a1 1 0 1 1-2 0Zm-8.5 4h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
