<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g8pjzt97a"/><path class="occpv--ie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gua-sha-sharp" /></template>
<style>
.g8pjzt97a {
  d: path("M6.04 9.4c3.45-1.26 5.69 1.83 8.56.51c1.43-.69 1.78-2.04 2.92-2.74a2.1 2.1-20 0 1 2.42 3.59l-.8.85l-.48 1.01l-.92-.22l-.47 1.01l-.92-.23l-.47 1.01l-.92-.22l-.47 1.01c-1.36 1.61-3.25 2.58-5.22 3.3A4.73 4.73-20 0 1 6.04 9.4Z");
}

.occpv--ie {
  d: path("m9 12.75l3.023 1.738L14.5 13.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
