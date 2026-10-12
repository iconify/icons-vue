<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n7eq391os"/><path class="f5t3rlb5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:apron-sharp" /></template>
<style>
.f5t3rlb5k {
  d: path("M9.5 14.25h5v3.5h-5V16.5Z");
}

.n7eq391os {
  d: path("M9 7.75V6a3 3 0 0 1 6 0v1.75m-7.75 0h9.5v1.5l1.5 2v10H5.75v-10l1.5-2Zm-1.5 3.5L3 12.75m15.25-1.5l2.75 1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
