<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yju6k55lu"/><path class="vvoib5sqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hut-sharp" /></template>
<style>
.vvoib5sqa {
  d: path("M10.25 21.25v-4.5h3.5v4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yju6k55lu {
  d: path("m3.27 13.21l8.21-8.67L12 4l.52.54l8.21 8.67l.52.54H2.75zM12 7.5l-2 6.25m2-6.25l2 6.25m-8.97 7l.44-6.5l.03-.5h13l.03.5l.44 6.5l.03.5H5z");
}

</style>
