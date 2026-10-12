<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pie2fvb8s"/><path class="cjwedsbgc"/><path class="rni8_7btp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:data-breach-sharp" /></template>
<style>
.cjwedsbgc {
  d: path("M4.75 6C4.75 7.8 8 9.25 12 9.25S19.25 7.8 19.25 6");
}

.pie2fvb8s {
  d: path("M4.75 6C4.75 4.2 8 2.75 12 2.75S19.25 4.2 19.25 6v12c0 1.8-3.25 3.25-7.25 3.25S4.75 19.8 4.75 18Z");
}

.rni8_7btp {
  d: path("M12.75 4.75L11 9l2.25 3.25l-2.25 3.5L12.5 20");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
