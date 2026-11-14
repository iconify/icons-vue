<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d9ggfsbaf"/><path class="trn770b_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:design-system-book" /></template>
<style>
.d9ggfsbaf {
  d: path("M5 19.5v-15a2 2 0 0 1 2-2h12v19H7a2 2 0 0 1-2-2a2 2 0 0 1 2-2h12");
}

.trn770b_n {
  d: path("m12 6.25l1.061 2.689L15.75 10l-2.689 1.061L12 13.75l-1.061-2.689L8.25 10l2.689-1.061Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
