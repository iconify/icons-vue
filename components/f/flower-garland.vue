<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="exy3cjnae"/><path class="tk-nsf1dw"/><path class="moorefbbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-garland" /></template>
<style>
.exy3cjnae {
  d: path("M4 6.5a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1 0-3Zm6.5 8.5a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1 0-3ZM17 6.5a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1 0-3Z");
}

.moorefbbc {
  d: path("M6.25 15q-2.75.25-2.75 3.25Q6.25 18 6.25 15Zm11.5 0q2.75.25 2.75 3.25Q17.75 18 17.75 15Z");
}

.tk-nsf1dw {
  d: path("M5.5 11q0 5.5 3.5 5.5m6 0q3.5 0 3.5-5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
