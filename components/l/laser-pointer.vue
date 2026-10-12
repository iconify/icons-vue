<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="u441slb_k"/><path class="su7wuov-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laser-pointer" /></template>
<style>
.su7wuov-l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 5.25h.01");
}

.u441slb_k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.1 20.1l-1.2-1.2q-1.06-1.06 0-2.12l4.88-4.88q1.06-1.06 2.12 0l1.2 1.2q1.06 1.06 0 2.12L7.22 20.1q-1.06 1.06-2.12 0m1.4-2.6l2-2m5.25-5.25L16.5 7.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
