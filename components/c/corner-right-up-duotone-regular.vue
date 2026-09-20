<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a_a8_nbmk"/><path class="ztm4xl13j"/><path class="kd5og0akl"/><path class="hil4ijbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-right-up-duotone-regular" /></template>
<style>
.a_a8_nbmk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h10V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hil4ijbut {
  d: path("m9 9 5 -5 5 5");
}

.kd5og0akl {
  d: path("M4 20h10V4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ztm4xl13j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 9 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
