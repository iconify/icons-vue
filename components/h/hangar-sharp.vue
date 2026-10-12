<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x0p5j-4im"/><path class="eso75mg5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hangar-sharp" /></template>
<style>
.eso75mg5n {
  d: path("M6.25 13.25a5.75 5.75 0 0 1 11.5 0M6.5 14.75h11v6.5h-11zm5.5 0v6.5");
}

.x0p5j-4im {
  d: path("M2.75 21.25V13.5a9.25 9 0 0 1 18.5 0v7.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
