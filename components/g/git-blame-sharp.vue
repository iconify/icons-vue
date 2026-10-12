<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ubdgkljhz"/><path class="x8l27_kwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-blame-sharp" /></template>
<style>
.ubdgkljhz {
  cx: 6.25px;
  cy: 8px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x8l27_kwb {
  d: path("M2.75 16.75a3.5 3.5 0 0 1 7 0v1.5h-7v-1Zm9.5-14h9v18.5h-9zm3 5.25h3m-3 4h3m-3 4H17");
}

</style>
