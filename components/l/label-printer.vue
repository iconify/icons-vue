<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="n4wxxuxlj"/><rect class="d7i1fbc4n"/><path class="rgs_lzdhn"/><path class="bebombs_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:label-printer" /></template>
<style>
.bebombs_y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 17.25h.01");
}

.d7i1fbc4n {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.n4wxxuxlj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 9.25v-4.5a2 2 0 0 1 2-2h5.5a2 2 0 0 1 2 2v4.5M9.75 6h4.5");
}

.rgs_lzdhn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 13h11.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
