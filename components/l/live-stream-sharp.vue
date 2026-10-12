<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bnr1nsbob"/><path class="n8dz26bgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:live-stream-sharp" /></template>
<style>
.bnr1nsbob {
  d: path("M2.75 9.25h18.5v12H2.75z");
}

.n8dz26bgq {
  d: path("m10.76 12.81l3.48 2.13l.51.31l-.51.31l-3.48 2.13l-.51.31v-5.5zM9 7.75l3-2.99l3 2.99M6.25 5.5a8.25 8.25 0 0 1 11.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
