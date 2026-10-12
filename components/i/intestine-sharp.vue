<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="evnl7wahe"/><path class="fl-zw2cnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:intestine-sharp" /></template>
<style>
.evnl7wahe {
  d: path("M2.75 19.75V3h18.5v18.25h-3V6H5.75v15.25h-3z");
}

.fl-zw2cnn {
  d: path("M9.25 9.25h6v3h-6.5v3h6.5v3h-6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
