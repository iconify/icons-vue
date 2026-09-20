<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwzg5so7l"/><path class="lj014sb8j"/><path class="q-rkk0b9q"/><path class="qt05i8bue"/><path class="cmz4hzb5r"/><path class="r-k_ekbaq"/><path class="f9t4wkbqv"/><path class="ugh4qacil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:error-handler-duotone-thin" /></template>
<style>
.cmz4hzb5r {
  d: path("M2 12h6l4 -4h5");
}

.f9t4wkbqv {
  d: path("m19 14 3 3");
}

.gwzg5so7l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h6l4 -4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lj014sb8j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 12 4 4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q-rkk0b9q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 14 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qt05i8bue {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m22 14 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r-k_ekbaq {
  d: path("m8 12 4 4h5");
}

.ugh4qacil {
  d: path("m22 14 -3 3");
}

</style>
