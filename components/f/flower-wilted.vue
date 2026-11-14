<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fhe0s72gk"/><path class="n2007tb7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-wilted" /></template>
<style>
.fhe0s72gk {
  d: path("M5 21.5V11c0-5 2.5-7.5 6-7.5c3 0 4.5 2 4.5 4.5");
}

.n2007tb7p {
  d: path("M13 12c0-2.5 1-4 2.5-4S18 9.5 18 12l.5 3.5l-1.75-2L15.5 16l-1.25-2.5l-1.75 2Zm-8 3c2 0 3.5 1.5 4 4c-2-.5-3.5-2-4-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
