<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u0nw6w7sx"/><path class="v4dqfac2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inverter-sharp" /></template>
<style>
.u0nw6w7sx {
  d: path("M2.75 2.75h18.5v18.5H2.75zM5.5 18.5l13-13M6 7.25h5M6 9.5h1.5m2 0H11");
}

.v4dqfac2y {
  d: path("M12.75 15.75c.9-2 1.85-2 2.75 0s1.85 2 2.75 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
