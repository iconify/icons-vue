<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y0o3v4bkb"/><path class="seq54xbbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-card-sharp" /></template>
<style>
.seq54xbbf {
  d: path("m17 11l1.75 2.042V14.1a1.75 1.75 0 0 1-3.5 0v-1.058z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y0o3v4bkb {
  d: path("M2.75 5.25h18.5v13.5H2.75zm0 4h18.5M6 14.75h5");
}

</style>
