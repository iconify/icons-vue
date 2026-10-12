<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rui-a3b0o"/><path class="qhufbmb5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heading-5-sharp" /></template>
<style>
.qhufbmb5s {
  d: path("M14.5 11.6a2 2 0 1 1 3.6 1.2l-3.6 3.95h4");
}

.rui-a3b0o {
  d: path("M3 4.75v14.5m5.75-14.5v14.5M3 12h5.75m3-4.75h9.5v12h-9.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
