<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="mnim1yb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-code-sharp" /></template>
<style>
.mnim1yb7e {
  d: path("M13.75 2.75v5.5h5.5m-9 2.75H9v3.25H8h1v3.25h1.25m3.5-6.5H15v3.25h1h-1v3.25h-1.25");
}

.rh2140hgr {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
