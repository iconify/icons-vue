<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ue5shzbko"/><path class="ef4ovwaua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:headset-sharp" /></template>
<style>
.ef4ovwaua {
  d: path("M3.75 12.75h4v6.5h-4zm12.5 0h4v6.5h-4z");
}

.ue5shzbko {
  d: path("M3.75 15v-3a8.25 8.25 0 0 1 16.5 0v3m-2 4.25v2H13.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
