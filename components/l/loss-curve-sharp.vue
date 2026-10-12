<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qmvt8fbnf"/><path class="dmq7ty1vb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loss-curve-sharp" /></template>
<style>
.dmq7ty1vb {
  d: path("M7 4.75C8.5 12.25 11.5 16 20.25 16.5");
}

.qmvt8fbnf {
  d: path("M3.25 3.25v17.5h17.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
