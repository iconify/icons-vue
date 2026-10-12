<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ox0kwwl2b"/><path class="ukawut6dp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blood-bank-sharp" /></template>
<style>
.ox0kwwl2b {
  d: path("M5.75 5.25h12.5v11.5H5.75zm4.25-.5v-2h4v2");
}

.ukawut6dp {
  d: path("M8 10.75h8v3.5H8v-1Zm4 6v4.5H7.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
