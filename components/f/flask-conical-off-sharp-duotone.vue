<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o4-575bqq"/><path class="quk2qgbrt"/><path class="ysqxkebtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-off-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o4-575bqq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.3058 8.3047L20.4757 20.4746L20.9308 21.6338C20.9765 21.7501 21.0001 21.874 21.0001 21.999C21.0001 22.5513 20.5523 22.9989 20.0001 22.999L4.0001 22.999C3.4478 22.999 3.0001 22.5513 3.0001 21.999C3.0001 21.874 3.0237 21.7501 3.0694 21.6338L8.3058 8.3047Z");
  stroke: none;
}

.quk2qgbrt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.0001 3H15.5001V7.81055L16.4317 10.1816L14.5704 10.9131L13.5694 8.36523C13.5238 8.24885 13.5001 8.12502 13.5001 8V3H10.5001V4.84277H8.50009V3H7.00009V1H17.0001V3Z");
  stroke: none;
}

.ysqxkebtz {
  d: path("M1.70709 1.70703L22.2929 22.2928");
}

</style>
