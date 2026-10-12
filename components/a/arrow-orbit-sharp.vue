<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rs8zf43rq"/><path class="vud8ldbsd"/><path class="iv6b4bbza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-orbit-sharp" /></template>
<style>
.iv6b4bbza {
  d: path("m3.84 8.89l3.97.51l-.51 3.97");
}

.rs8zf43rq {
  d: path("M14 12a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.vud8ldbsd {
  d: path("M13.95 6.38A9 4.5-30 1 1 7.81 9.4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
