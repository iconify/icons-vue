<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fs93di69o"/><circle class="u9zd92bgx"/><circle class="t21ih2v7z"/><path class="lq0twvbsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boombox-sharp" /></template>
<style>
.fs93di69o {
  d: path("M2.75 8h18.5v12.5H2.75zM6.5 8V4h11v4");
}

.lq0twvbsf {
  d: path("M10.75 11.5h2.5");
}

.t21ih2v7z {
  cx: 16px;
  cy: 14.75px;
  r: 2.5px;
}

.u9zd92bgx {
  cx: 8px;
  cy: 14.75px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
