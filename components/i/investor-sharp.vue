<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="se6ixebfq"/><path class="emn90tj_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:investor-sharp" /></template>
<style>
.emn90tj_k {
  d: path("M3.5 20.25h8.75v-.75c0-3.62-2.17-6.25-4.75-6.25s-4.75 2.63-4.75 6.25v.75zm11.75-10h6v11h-6zm0 3.75h6m-6 3.5h6");
}

.se6ixebfq {
  cx: 7.5px;
  cy: 7.75px;
  r: 3.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
