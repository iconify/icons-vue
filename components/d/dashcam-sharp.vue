<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ed_l79blo"/><circle class="z0np8cblh"/><path class="ttidu-b1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dashcam-sharp" /></template>
<style>
.ed_l79blo {
  d: path("M9.5 2.75h5v2.5h-5zm2.5 2.5v2.5m-9.25 0h18.5v11H2.75z");
}

.ttidu-b1p {
  d: path("M6 11h1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z0np8cblh {
  cx: 14.5px;
  cy: 13.25px;
  r: 3px;
}

</style>
