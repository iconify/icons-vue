<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tode6-bmt"/><path class="bi03qtb5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-fuse-sharp" /></template>
<style>
.bi03qtb5r {
  d: path("M7.5 9.75h3l3-2.5h3M6 13h3v6H6zm9 0h3v6h-3z");
}

.tode6-bmt {
  d: path("M3.5 4h17v9h-17z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
