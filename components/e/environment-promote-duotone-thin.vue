<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vws5wpblq"/><path class="o5j4oxb1h"/><path class="i43uzzbnk"/><path class="ri2m-q_tv"/><path class="hqoi59sxr"/><path class="y5493mbgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:environment-promote-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hqoi59sxr {
  d: path("M12 9v7");
}

.i43uzzbnk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 11.5 12 9l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o5j4oxb1h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.vws5wpblq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y5493mbgk {
  d: path("M9.5 11.5 12 9l2.5 2.5");
}

</style>
