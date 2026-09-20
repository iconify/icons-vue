<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zl6g0h25d"/><path class="x__poibgg"/><path class="kzghqcc0v"/><path class="k455i0bwi"/><path class="cjsg0ab2y"/><path class="fjkpt106v"/><path class="b9coo-b0i"/><path class="i7tgsrb7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:beaufort-duotone-thin" /></template>
<style>
.b9coo-b0i {
  d: path("M10.5 20v-9h5v9");
}

.cjsg0ab2y {
  d: path("M2 20h20");
}

.fjkpt106v {
  d: path("M3 20v-5h5v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7tgsrb7i {
  d: path("M18 20V6h3v14");
}

.k455i0bwi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 20V6h3v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kzghqcc0v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 20v-9h5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x__poibgg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20v-5h5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zl6g0h25d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
