<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_nawgbcx"/><path class="u_f-byj6m"/><path class="iadgaoe9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dovecote" /></template>
<style>
.iadgaoe9z {
  d: path("M10 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 5.5v3.5");
}

.o_nawgbcx {
  d: path("m4 10l8-7l8 7");
}

.u_f-byj6m {
  d: path("M6 8.25V18h12V8.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
