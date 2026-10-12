<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qkdnznu5t"/><path class="bet8m4b6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-step-down-sharp" /></template>
<style>
.bet8m4b6f {
  d: path("m14.25 16.5l3 3l3-3");
}

.qkdnznu5t {
  d: path("M3.75 3.75h5v5h5v5h3.5v5.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
