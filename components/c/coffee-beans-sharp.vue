<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pxze97d6j"/><path class="qki09f3ff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coffee-beans-sharp" /></template>
<style>
.pxze97d6j {
  d: path("M4.65 11.97a5 3.25-48 1 1 6.7-7.44a5 3.25-48 1 1-6.7 7.44Zm8 7.25a5 3.25-48 1 1 6.7-7.44a5 3.25-48 1 1-6.7 7.44Z");
}

.qki09f3ff {
  d: path("m5.83 10.67l1.77-.63l.4-1.79l.4-1.79l1.77-.63m3.66 12.09l1.77-.63l.4-1.79l.4-1.79l1.77-.63");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
