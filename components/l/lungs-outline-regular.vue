<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nnwao2bjn"/><path class="gn4faibes"/><path class="z60jnpbbk"/><path class="x7f1-zoxp"/><path class="frl4q-b1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lungs-outline-regular" /></template>
<style>
.frl4q-b1m {
  d: path("M15 13v7a5 5 0 0 0 5 -5c0 -2 -2 -2 -5 -2");
}

.gn4faibes {
  d: path("m12 10 -3 3");
}

.nnwao2bjn {
  d: path("M12 3v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x7f1-zoxp {
  d: path("M9 13v7a5 5 0 0 1 -5 -5c0 -2 2 -2 5 -2");
}

.z60jnpbbk {
  d: path("m12 10 3 3");
}

</style>
