<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bhlnjacrs"/><path class="rpc47h1ti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carousel-horse-sharp" /></template>
<style>
.bhlnjacrs {
  d: path("M12 2.75V10m0 7.25v4M5.5 12.5V10h9.25L17 6.5l.923-1.385L19.25 6l1.5 1l.833.667L21 8.5l-.75 1l-1.5-.5L17 12.25v5H5.5V14.5Z");
}

.rpc47h1ti {
  d: path("M8 17.25L6.75 21m8-4.75L17 17.5l-.5 2.25m-11-8.25H3.167L2.75 14");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
