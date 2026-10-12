<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ttgrz1bqg"/><path class="dpv3wchbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-stack-sharp" /></template>
<style>
.dpv3wchbo {
  d: path("M2.75 9.25v-2h5.5l2 2h8v12H2.75v-2Z");
}

.ttgrz1bqg {
  d: path("M5.75 7.25v-4.5H11l2 2h8.25V18");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
