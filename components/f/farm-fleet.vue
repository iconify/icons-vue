<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f8zh8l_by"/><path class="n95_a_bxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-fleet" /></template>
<style>
.f8zh8l_by {
  d: path("M2.5 15.5v-5H12v-4a1 1 0 0 1 1-1h3.5l3 4.5h1a1 1 0 0 1 1 1v4.5Z");
}

.n95_a_bxy {
  d: path("M3.75 6h5.5v4.5h-5.5ZM5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
