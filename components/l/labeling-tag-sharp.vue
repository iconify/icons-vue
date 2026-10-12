<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bnpgwbctb"/><path class="auo77bbyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:labeling-tag-sharp" /></template>
<style>
.auo77bbyv {
  d: path("M6.75 5.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5Zm7 12.75L16 20.5l5-5");
}

.bnpgwbctb {
  d: path("M4.25 2.75h6l1.06 1.06l4.88 4.88l1.06 1.06l-1.06 1.06l-5.38 5.38l-1.06 1.06l-1.06-1.06l-4.88-4.88l-1.06-1.06v-7.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
