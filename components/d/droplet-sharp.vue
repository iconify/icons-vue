<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xb0dygbcb"/><path class="j14zp8b0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:droplet-sharp" /></template>
<style>
.j14zp8b0q {
  d: path("M8.75 14.75V18H12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xb0dygbcb {
  d: path("M12 2.75C8.5 7 5.25 10.75 5.25 14.5a6.75 6.75 0 0 0 13.5 0c0-3.75-3.25-7.5-6.75-11.75Z");
}

</style>
