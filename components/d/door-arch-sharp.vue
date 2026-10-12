<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gqho0ybfa"/><path class="o6bip-kik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:door-arch-sharp" /></template>
<style>
.gqho0ybfa {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.25V10a6.5 6.5 0 0 1 13 0v11.25ZM12 3.5v17.75");
}

.o6bip-kik {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 14h.01m3.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
