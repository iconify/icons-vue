<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hnz0kibag"/><circle class="fv8wiubss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dslr-camera-sharp" /></template>
<style>
.fv8wiubss {
  cx: 11px;
  cy: 14.25px;
  r: 3px;
}

.hnz0kibag {
  d: path("M4 8h4l.3-1.21l.65-2.58l.3-1.21h3.5l.3 1.21l.65 2.58L14 8h4.5v1.25h2.75v11H2.75V8z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
