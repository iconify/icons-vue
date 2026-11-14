<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k4s89sbqk"/><path class="qa3wbl5ny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:building-defect" /></template>
<style>
.k4s89sbqk {
  d: path("M15.2 17H3V3h18v14h-.2");
}

.qa3wbl5ny {
  d: path("M10 3L8 7l3.5 3.5l-3 3.5l1.5 3m8-2.25v3.5M18 21h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
