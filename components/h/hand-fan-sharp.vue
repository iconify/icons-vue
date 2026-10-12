<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zlv3sbbar"/><path class="k3nhh1-fh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-fan-sharp" /></template>
<style>
.k3nhh1-fh {
  d: path("M9.5 13.9L12 11l2.5 2.9m-2.5.35v7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zlv3sbbar {
  d: path("M12 14.25c-4.5 0-7.25-2.25-7.25-5.75S7.5 2.75 12 2.75S19.25 5 19.25 8.5S16.5 14.25 12 14.25Z");
}

</style>
