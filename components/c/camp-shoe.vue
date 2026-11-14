<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="shx5-6b4s"/><path class="epq2fb9nh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camp-shoe" /></template>
<style>
.epq2fb9nh {
  d: path("M15.5 10c-1.25 2.5-1.25 5.5-.5 8");
}

.shx5-6b4s {
  d: path("M2.5 13.5v3A1.5 1.5 0 0 0 4 18h15.5a2 2 0 0 0 2-2c0-3-3-4.5-6-6l-4-3.5c-1-.75-2-.5-2.5.5l-1.5 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
