<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p7-9zrxsb"/><path class="sxr7glbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:context-window-sharp" /></template>
<style>
.p7-9zrxsb {
  d: path("M3.75 2.75h16.5v18.5H3.75zm3.5 3h9.5m-9.5 12.5h6");
}

.sxr7glbro {
  d: path("M6 9.75h12v4.5H6zM8.75 12h6.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
