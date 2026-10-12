<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h8jqndbwc"/><path class="nacvh6tbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:billing-sharp" /></template>
<style>
.h8jqndbwc {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.5 3.75h7.5");
}

.nacvh6tbl {
  d: path("m13.71 11.79l-.435-1.08H10.29v1.33c0 1.77 3.56.99 3.56 2.88v1.36h-3.18l-.54-1.08M12 9.63v1.08m0 5.58v1.08");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
