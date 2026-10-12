<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="leq-9tb_y"/><path class="tz4_z3pdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hazard-flammable-sharp" /></template>
<style>
.leq-9tb_y {
  d: path("m13.59 3.84l6.57 6.57L21.75 12l-1.59 1.59l-6.57 6.57L12 21.75l-1.59-1.59l-6.57-6.57L2.25 12l1.59-1.59l6.57-6.57L12 2.25z");
}

.tz4_z3pdq {
  d: path("M12 6.75c2.5 2.25 3.75 4.25 3.75 6.5a3.75 3.75 0 0 1-7.5 0v-2L10 9.5l.375 1.875l1.125.375c0-2 .25-3.5.5-5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
