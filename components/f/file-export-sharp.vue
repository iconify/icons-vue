<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oxvm4ab5j"/><path class="nyeq5nb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-export-sharp" /></template>
<style>
.nyeq5nb4f {
  d: path("M13.75 2.75v5.5h5.5m-8 6.25h10m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

.oxvm4ab5j {
  d: path("M19.25 11.25v-3l-5.5-5.5h-9v18.5h14.5v-3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
