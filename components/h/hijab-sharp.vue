<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ak-925b-h"/><path class="nlx6-irvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hijab-sharp" /></template>
<style>
.ak-925b-h {
  d: path("M3 21.25c0-3.75 2-5.75 4-6.5C5.75 13 5.25 11 5.25 9.5a6.75 6.75 0 0 1 13.5 0c0 1.5-.5 3.5-1.75 5.25c2 .75 4 2.75 4 6.5Z");
}

.nlx6-irvm {
  d: path("M12 6a3.5 4.25 0 1 1 0 8.5A3.5 4.25 0 1 1 12 6ZM8.75 17.75L12 19.194l3.25-1.444");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
