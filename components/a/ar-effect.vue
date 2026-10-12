<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gb7pqmztb"/><path class="hf-4tkb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ar-effect" /></template>
<style>
.gb7pqmztb {
  d: path("M2.75 7.5V5.75a3 3 0 0 1 3-3H7.5m9 0h1.75a3 3 0 0 1 3 3V7.5m0 9v1.75a3 3 0 0 1-3 3H16.5m-9 0H5.75a3 3 0 0 1-3-3V16.5m9.94-9.6l3.37 1.95q.69.4.69 1.2v3.9q0 .8-.69 1.2l-3.37 1.95q-.69.4-1.38 0l-3.37-1.95q-.69-.4-.69-1.2v-3.9q0-.8.69-1.2l3.37-1.95q.69-.4 1.38 0");
}

.hf-4tkb5q {
  d: path("M7.75 9.6L12 12l4.25-2.4M12 12v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
