<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n4i5bcb1r"/><path class="ix77fhbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hull-ship-sharp" /></template>
<style>
.ix77fhbes {
  d: path("M15 8.75a2.5 2.5 0 1 0 0 5a2.5 2.5 0 1 0 0-5Zm-3.5 2.5h7m-15.75 9.5C4 20.75 4 20 5.25 20s1.25.75 2.5.75S9 20 10.25 20s1.25.75 2.5.75S14 20 15.25 20s1.25.75 2.5.75S19 20 20.25 20");
}

.n4i5bcb1r {
  d: path("M3.5 6h15.75l.37.65l1.26 2.2l.37.65l-.25.71l-2 5.58l-.25.71H5.5l-.19-.73l-2.37-9.04L2.75 6z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
