<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a6mcbq4tm"/><path class="wc7ji-byo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cuboid-sharp" /></template>
<style>
.a6mcbq4tm {
  d: path("M4.25 10.5H15l.95-.82l3.6-3.11l.95-.82v8l-.95.82l-3.6 3.11l-.95.82H3v-8z");
}

.wc7ji-byo {
  d: path("m3.95 9.68l3.6-3.11l.95-.82h12l-.95.82l-3.6 3.11l-.95.82H3zM15 11v7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
