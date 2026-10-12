<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ub4gopnmb"/><path class="lsd97cb7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loafers-sharp" /></template>
<style>
.lsd97cb7u {
  d: path("m11 12.75l3.111.444L16 12.25m-12.75 3H21");
}

.ub4gopnmb {
  d: path("M3.25 19.25V11l-.025-1.25L4.45 10c2.05.4 4.3.5 6.55.25l1.5-.25h1.917l2.083 1.25l2.6 1.6l2.15 1.29v5.11H11.5l-1-1.5H8l-1 1.5H3.25v-1Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
