<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x_j-lkb3f"/><circle class="pc0povb4n"/><path class="dj9619bqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:contact-book-sharp" /></template>
<style>
.dj9619bqg {
  d: path("M8.5 16.25L9.4 14h5.2l.9 2.25");
}

.pc0povb4n {
  cx: 12px;
  cy: 10px;
  r: 2.25px;
}

.x_j-lkb3f {
  d: path("M4.75 2.75h14.5v18.5H4.75zM3.25 7.5h3m-3 4.5h3m-3 4.5h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
