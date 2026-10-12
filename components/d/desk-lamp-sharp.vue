<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nonyezbbm"/><path class="vj2kgkiaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:desk-lamp-sharp" /></template>
<style>
.nonyezbbm {
  d: path("m13.79 5.21l-.58.58l-.71.71l.4.92l1.95 4.41l.4.92l.71-.71l4.08-4.08l.71-.71l-.92-.4l-4.41-1.95l-.92-.4z");
}

.vj2kgkiaz {
  d: path("M8.75 21L5.5 13.75l8-8.25M4.25 21h9");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
