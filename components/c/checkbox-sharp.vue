<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nciaxcb6w"/><path class="kjimvnuvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:checkbox-sharp" /></template>
<style>
.kjimvnuvm {
  d: path("M8 12.25L10.75 15L16 9.5");
}

.nciaxcb6w {
  d: path("M3.25 3.25h17.5v17.5H3.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
