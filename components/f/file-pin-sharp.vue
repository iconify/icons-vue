<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z_vrkxb-f"/><path class="i-8_mtrbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-pin-sharp" /></template>
<style>
.i-8_mtrbu {
  d: path("M13.75 2.75v5.5h5.5m-11 4h4m2.5 5.5h5.5m-4.5 0l.5-3.5h2.5l.5 3.5m-1.75 0v3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_vrkxb-f {
  d: path("M11.75 21.25h-7V2.75h9l5.5 5.5v3.5");
}

</style>
