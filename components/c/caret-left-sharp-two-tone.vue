<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jz7e0cb1d"/><path class="nw0f-gbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-left-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jz7e0cb1d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.4961 12.8638C4.8346 12.4779 4.8346 11.5221 5.4961 11.1362L17.4961 4.1362C18.1628 3.7473 19 4.2282 19 5L19 19C19 19.7718 18.1628 20.2527 17.4961 19.8638L5.4961 12.8638Z");
  stroke: none;
}

.nw0f-gbpt {
  d: path("M6 12L18 19L18 5L6 12Z");
}

</style>
