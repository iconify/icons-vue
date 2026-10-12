<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lmi8ozq6o"/><path class="p4u_u8p5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:butter-sharp" /></template>
<style>
.lmi8ozq6o {
  d: path("M6 16.75v-5.5L8.75 8.5H19.5V14l-2.75 2.75Z");
}

.p4u_u8p5u {
  d: path("M6 11.25h10.75v5.5m0-5.5L19.5 8.5M2.75 17.75v2h18.5v-2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
