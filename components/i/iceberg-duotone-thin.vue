<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wkiqe6rhb"/><path class="m1muscbxs"/><path class="rvoc0ob8r"/><path class="es-ot3p7v"/><path class="b--mi0m0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:iceberg-duotone-thin" /></template>
<style>
.b--mi0m0m {
  d: path("m8 12 6 6 6 -6");
}

.es-ot3p7v {
  d: path("M18 11h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1muscbxs {
  d: path("m6 11 6 -6 6 6Z");
}

.rvoc0ob8r {
  d: path("M2 11h4");
}

.wkiqe6rhb {
  fill: currentColor;
  d: path("m6 11 6 -6 6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
