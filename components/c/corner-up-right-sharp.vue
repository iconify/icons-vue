<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xgu99_cfi"/><path class="ft6epebfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corner-up-right-sharp" /></template>
<style>
.ft6epebfu {
  d: path("m15.5 13l3.75-3.75L15.5 5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xgu99_cfi {
  d: path("M4.25 19.75V9.25h15");
}

</style>
