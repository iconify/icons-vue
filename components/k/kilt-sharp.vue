<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fcdahhbsy"/><path class="yrmj6xxuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kilt-sharp" /></template>
<style>
.fcdahhbsy {
  d: path("M7 3.5h11l.13.99l1.99 14.77l.13.99H3.75l.13-.99L5.87 4.49L6 3.5zm-.75 3h11.5M8.5 15v4.5m7-4.5v4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrmj6xxuq {
  d: path("M11 9.5h2.75l.12.74l.51 3.02l.12.74l-.61.43l-1.28.89l-.61.43l-.61-.43l-1.28-.89L9.5 14l.12-.74l.51-3.02l.12-.74z");
}

</style>
