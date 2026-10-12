<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rd6dt9v-d"/><path class="shslhfb5e"/><circle class="h_tsn8bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hurricane-eye-sharp" /></template>
<style>
.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.rd6dt9v-d {
  d: path("M12 16.5a4.5 4.5 0 0 1 0-9c4.5 0 9-1.5 9-4.5");
}

.shslhfb5e {
  d: path("M12 7.5a4.5 4.5 0 0 1 0 9c-4.5 0-9 1.5-9 4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
