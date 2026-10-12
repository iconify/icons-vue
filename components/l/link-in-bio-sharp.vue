<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l5g864bjc"/><circle class="hhov-gbog"/><path class="lzhfyj0gc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:link-in-bio-sharp" /></template>
<style>
.hhov-gbog {
  cx: 12px;
  cy: 7px;
  r: 1.5px;
}

.l5g864bjc {
  d: path("M5.25 2.75h13.5v18.5H5.25z");
}

.lzhfyj0gc {
  d: path("M8.75 11h6.5v2h-6.5zm0 4.5h6.5v2h-6.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
