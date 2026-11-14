<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nusna_vpp"/><path class="mi9qgdbbz"/><path class="lujjg8ezb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brake-drum" /></template>
<style>
.lujjg8ezb {
  d: path("M7.5 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3-5.5h.01m4.74 8.25h.01m-9.51 0h.01");
}

.mi9qgdbbz {
  d: path("M10.5 4h3a8 8 0 0 1 0 16h-3");
}

.nusna_vpp {
  d: path("M2.5 12a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
