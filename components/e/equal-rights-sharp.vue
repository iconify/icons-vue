<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="crap3dykr"/><path class="omr5pttzl"/><circle class="tc9ytgh7v"/><path class="sh_7mlblj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:equal-rights-sharp" /></template>
<style>
.crap3dykr {
  cx: 5.5px;
  cy: 7.5px;
  r: 2.25px;
}

.omr5pttzl {
  d: path("M2.75 18.5v-3a2.75 2.75 0 0 1 5.5 0v4h-5.5z");
}

.sh_7mlblj {
  d: path("M15.75 18.5v-3a2.75 2.75 0 0 1 5.5 0v4h-5.5zM10 11.75h4M10 15h4");
}

.tc9ytgh7v {
  cx: 18.5px;
  cy: 7.5px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
