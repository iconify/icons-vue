<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zrf8f-y4q"/><circle class="v-o_6u8ph"/><path class="md02fs7is"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:indoor-camera-off-sharp" /></template>
<style>
.md02fs7is {
  d: path("m3.25 3.25l17.5 17.5");
}

.v-o_6u8ph {
  cx: 12px;
  cy: 13.25px;
  r: 3.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zrf8f-y4q {
  d: path("M3.25 9.25v-2h4.1l1.1-1.85l.433-.751l.867.001h4.5l.867-.001l.433.751l1.1 1.85h4.1v13H3.25v-2.5Z");
}

</style>
