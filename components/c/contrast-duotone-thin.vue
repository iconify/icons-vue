<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhy5nnbig"/><path class="i340fwbtf"/><path class="o_ssmh9ez"/><path class="d0ge12qkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:contrast-duotone-thin" /></template>
<style>
.d0ge12qkl {
  d: path("M12 3a9 9 0 0 1 0 18Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i340fwbtf {
  fill: currentColor;
  d: path("M12 3a9 9 0 0 1 0 18Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.zhy5nnbig {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
