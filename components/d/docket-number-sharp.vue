<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="umnd40k6s"/><path class="cl3rvm8ke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:docket-number-sharp" /></template>
<style>
.cl3rvm8ke {
  d: path("M10.25 11.25L12.5 9.5v8m-2.25 0h4.5");
}

.umnd40k6s {
  d: path("M4.75 2.75h14.5v18.5H4.75zM8.25 6h7.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
