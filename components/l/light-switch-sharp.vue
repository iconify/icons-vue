<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l5g864bjc"/><path class="f-b0yfbli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:light-switch-sharp" /></template>
<style>
.f-b0yfbli {
  d: path("M9.5 6.75h5v10.5h-5zm0 5.25h5");
}

.l5g864bjc {
  d: path("M5.25 2.75h13.5v18.5H5.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
