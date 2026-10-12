<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dezl2kbky"/><path class="ble7z0bpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coolant-level-sharp" /></template>
<style>
.ble7z0bpx {
  d: path("M7.5 14.5c1.5-1 3 1 4.5 0s3 1 4.5 0v4.25h-9V18Z");
}

.dezl2kbky {
  d: path("M9 2.75h6v3H9zm-4.5 3h15v15.5h-15z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
