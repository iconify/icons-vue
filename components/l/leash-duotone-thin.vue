<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyvm7xbin"/><path class="ca4aen3yr"/><path class="lo7kp72nh"/><path class="n2em18brm"/><path class="fah6drbfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leash-duotone-thin" /></template>
<style>
.ca4aen3yr {
  fill: currentColor;
  d: path("M16 18h3v3h-3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fah6drbfn {
  d: path("M16 18h3v3h-3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lo7kp72nh {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.n2em18brm {
  d: path("M9 10c4 2 6 5 7 8");
}

.yyvm7xbin {
  fill: currentColor;
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
