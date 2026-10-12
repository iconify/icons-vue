<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kepqf7b_i"/><path class="yo_hj2bgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heptagon" /></template>
<style>
.kepqf7b_i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.58 3.41l4.47 2.15q1.57.76 1.96 2.47l1.11 4.83q.39 1.71-.71 3.08l-3.09 3.88q-1.09 1.36-2.84 1.36H9.52q-1.75 0-2.84-1.36l-3.09-3.88q-1.1-1.37-.71-3.08l1.11-4.83q.39-1.71 1.96-2.47l4.47-2.15q1.58-.76 3.16 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yo_hj2bgd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.4h.01");
}

</style>
