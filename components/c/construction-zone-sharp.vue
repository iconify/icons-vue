<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bxz87k65a"/><path class="ro0e9_bbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:construction-zone-sharp" /></template>
<style>
.bxz87k65a {
  d: path("m13.24 3.99l6.77 6.77L21.25 12l-1.24 1.24l-6.77 6.77L12 21.25l-1.24-1.24l-6.77-6.77L2.75 12l1.24-1.24l6.77-6.77L12 2.75z");
}

.ro0e9_bbz {
  d: path("M8.25 14.75h7.5m-6.75 0a3 3 0 0 1 6 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
