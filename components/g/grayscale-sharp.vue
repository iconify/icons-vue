<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w677y9sfz"/><path class="ds7rev47f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grayscale-sharp" /></template>
<style>
.ds7rev47f {
  d: path("M15.25 3.34a9.25 9.25 0 0 1 0 17.32ZM9 10.5l4.25-4.25M9 15l4.25-4.25M9.5 19l3.75-3.75");
}

.w677y9sfz {
  d: path("M12 2.75a9.25 9.25 0 1 0 0 18.5a9.25 9.25 0 1 0 0-18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
