<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="njma4u3xr"/><path class="u0w8rt-ho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heart-broken-sharp" /></template>
<style>
.njma4u3xr {
  d: path("M12 20.25h-.62l-.48-.4C7.6 17.1 3.25 13.6 3.25 8.9C3.25 6.2 5.3 4 7.9 4h2.371L12 6.2L13.729 4H16.1c2.6 0 4.65 2.2 4.65 4.9c0 4.7-4.35 8.2-7.65 10.95l-.48.4z");
}

.u0w8rt-ho {
  d: path("M12 6.5L10.75 10l2.5 2.75l-1.5 3.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
