<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qlv1vmmbf"/><path class="pmq4fab-l"/><path class="kj1tfs36l"/><path class="a3ch5yb2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:beer-mug-duotone-thin" /></template>
<style>
.a3ch5yb2h {
  d: path("M5 10h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kj1tfs36l {
  d: path("M15 9c3 0 4 2 4 4s-1 4 -4 4");
}

.pmq4fab-l {
  d: path("M5 6h10v15H5Z");
}

.qlv1vmmbf {
  fill: currentColor;
  d: path("M5 6h10v15H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
