<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="x4b_fdcyj"/><path class="fxl-pccbe"/><rect class="mjsrlb0zu"/><path class="z_b3_fbbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blender" /></template>
<style>
.fxl-pccbe {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 10.75l2.5-1.5l2.5 1.5");
}

.mjsrlb0zu {
  width: 10px;
  height: 4.75px;
  x: 7px;
  y: 16.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.x4b_fdcyj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.75h9q1.25 0 1.06 1.24l-1.37 8.77Q16 14 14.75 14h-5.5Q8 14 7.81 12.76L6.44 3.99Q6.25 2.75 7.5 2.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z_b3_fbbi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.88h.01");
}

</style>
