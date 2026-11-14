<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="al3c9pocs"/><path class="qyyk4hkuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-windshield-crack" /></template>
<style>
.al3c9pocs {
  d: path("M4 18L7 6h10l3 12Z");
}

.qyyk4hkuw {
  d: path("m12 6l-1 4l2.5 2.5L12 18m-1-8l-3 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
