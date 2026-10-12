<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="r82p9vbru"/><path class="jumqf8ewo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gravity-assist-sharp" /></template>
<style>
.jumqf8ewo {
  d: path("M2.75 6.75H12a7.25 7.25 0 0 1 3.06 13.82m2.42.65l-2.42-.65l1.06-2.27");
}

.r82p9vbru {
  cx: 12px;
  cy: 14px;
  r: 3.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
