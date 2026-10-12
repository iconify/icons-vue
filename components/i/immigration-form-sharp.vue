<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="iiqlhmbpr"/><path class="hmi_qewqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:immigration-form-sharp" /></template>
<style>
.hmi_qewqf {
  d: path("M8.25 16h7M13 13.75L15.25 16L13 18.25");
}

.iiqlhmbpr {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.5 4h1.5m2 0h4M8.25 10h1.5m2 0h4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
