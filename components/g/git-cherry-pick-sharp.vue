<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="mtl-gzbxy"/><circle class="ry3mbqbyv"/><path class="agnbp9bca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-cherry-pick-sharp" /></template>
<style>
.agnbp9bca {
  d: path("M6.75 2.75V16.5m10.5-13.75v7m0 4.5v7m-3-9.25h-4.5m2-2.25L9.5 12l2.25 2.25");
}

.mtl-gzbxy {
  cx: 6.75px;
  cy: 18.75px;
  r: 2.25px;
}

.ry3mbqbyv {
  cx: 17.25px;
  cy: 12px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
