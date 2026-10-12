<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uf5xj6blp"/><circle class="s2ji9x41d"/><circle class="sjhq4_bif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:golf-cart-sharp" /></template>
<style>
.s2ji9x41d {
  cx: 7px;
  cy: 17px;
  r: 2.5px;
}

.sjhq4_bif {
  cx: 17px;
  cy: 17px;
  r: 2.5px;
}

.uf5xj6blp {
  d: path("M3.25 3.5h17.5M5 3.5V12m13.5-8.5V12M7.75 12V8.25h4m4 3.75L14.5 8.75H13M2.75 12h18.5v4.75H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
