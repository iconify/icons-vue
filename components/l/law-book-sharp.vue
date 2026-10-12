<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oar9qtoiz"/><path class="nzuz6w5pm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:law-book-sharp" /></template>
<style>
.nzuz6w5pm {
  d: path("M19.25 16.25H4.75v2.5M8.75 7h6.5m-6.5 3.25h4");
}

.oar9qtoiz {
  d: path("M19.25 2.75v18.5H4.75V2.75h2.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
