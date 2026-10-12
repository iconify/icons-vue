<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xj_2eg09s"/><path class="umcq0cbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-smile-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.umcq0cbop {
  d: path("M21 10L12 2.9963L3 10L3 21L21 21ZM9 9.5L9 12.5M15 9.5L15 12.5M8.7071 15.2071L9 15.5C10 16.5 11 17 12 17C13 17 14 16.5 15 15.5L15.2929 15.2071");
}

.xj_2eg09s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.3857 2.2071C11.7469 1.926 12.2531 1.926 12.6143 2.2071L21.6143 9.211C21.8575 9.4005 22 9.6917 22 10.0001L22 21.0001C21.9998 21.5522 21.5522 22.0001 21 22.0001L3 22.0001C2.4478 22.0001 2.0002 21.5522 2 21.0001L2 10.0001C2 9.6917 2.1425 9.4005 2.3857 9.211L11.3857 2.2071Z");
  stroke: none;
}

</style>
