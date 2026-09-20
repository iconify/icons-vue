<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0jamibkm"/><path class="bn_pu6j-z"/><path class="gco2r_19v"/><path class="pljtrccyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:folder-off-duotone-thin" /></template>
<style>
.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.gco2r_19v {
  d: path("m10 11 4 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pljtrccyg {
  d: path("m14 11 -4 4");
}

.r0jamibkm {
  fill: currentColor;
  d: path("M20 7v13H4V4h5l3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
