<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fxq259q4w"/><circle class="ycfjfqbdy"/><path class="sanpeybap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:build-status-sharp" /></template>
<style>
.fxq259q4w {
  d: path("M4.75 3.25h8.75l.67.74l.91 1.02l.67.74v2.5h-12v-5zm4.5 5v12.5");
}

.sanpeybap {
  d: path("m15.75 17.1l1 1l1.75-1.85");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ycfjfqbdy {
  cx: 17.25px;
  cy: 17px;
  r: 3.5px;
}

</style>
