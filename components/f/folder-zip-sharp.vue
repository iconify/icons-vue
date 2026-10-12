<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d_jdfdc1d"/><path class="lsu570b_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-zip-sharp" /></template>
<style>
.d_jdfdc1d {
  d: path("M2.75 7.25v-2.5h7.1l.6.8L11.55 7l.6.8h9.1v13.45H2.75v-2.5ZM12 7.5V15m-1.75-5H12m0 1.5h1.75m-3.5 1.5H12");
}

.lsu570b_x {
  d: path("M10.75 15h2.5v4h-2.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
