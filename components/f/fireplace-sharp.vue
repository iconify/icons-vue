<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pwe41bbpc"/><path class="h2fw37b2o"/><path class="vextnibpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fireplace-sharp" /></template>
<style>
.h2fw37b2o {
  d: path("M7.75 21.25V14.5a4.25 4.25 0 0 1 8.5 0v6.75");
}

.pwe41bbpc {
  d: path("M2.75 5.25h18.5m-16.5 2.5h14.5v13.5H4.75Z");
}

.vextnibpp {
  d: path("m12 14.25l1.6 1.44v1.46a1.6 1.6 0 0 1-3.2 0v-1.46z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
