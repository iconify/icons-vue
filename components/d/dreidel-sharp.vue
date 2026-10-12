<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="i927goqjp"/><path class="gjsxbh4hp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dreidel-sharp" /></template>
<style>
.gjsxbh4hp {
  d: path("M9 10v2.25a3 3 0 0 0 6 0V10m-3 0v5.25");
}

.i927goqjp {
  d: path("M12 2.75V7.5m-4.75 0H18v6.75l-.81.95l-4.38 5.1l-.81.95l-.81-.95l-4.38-5.1l-.81-.95V7.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
