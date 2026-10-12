<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y3658bbcq"/><circle class="xwv91sd-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coordinate-plane-sharp" /></template>
<style>
.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xwv91sd-e {
  cx: 16.75px;
  cy: 7.25px;
  r: 1.75px;
}

.y3658bbcq {
  d: path("M12 2.75v18.5M2.75 12h18.5M7 10.75v2.5M10.75 17h2.5");
}

</style>
