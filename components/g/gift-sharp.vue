<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g6_ak4fap"/><path class="o0aijxb6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gift-sharp" /></template>
<style>
.g6_ak4fap {
  d: path("M3.25 7.25h17.5v4.25H3.25zM4.75 14h14.5v7.25H4.75v-2Z");
}

.o0aijxb6o {
  d: path("M12 7.25v14m0-14H8.75a2 2 0 1 1 0-4c1.75 0 2.75 2 3.25 4m0 0h3.25a2 2 0 1 0 0-4c-1.75 0-2.75 2-3.25 4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
