<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k30r-ociw"/><path class="i6-t9nb6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:didgeridoo-sharp" /></template>
<style>
.i6-t9nb6o {
  d: path("M20.02 7.52a2.5 1.25 45 0 1-3.54-3.54m-2.97 3.39l3.12 3.12m-5.44-.48l2.8 2.8");
}

.k30r-ociw {
  d: path("M16.48 3.98L3.87 18.37l-.794.959l1.76 1.76l.794-.959L20.02 7.52a2.5 1.25 45 0 0-3.54-3.54Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
