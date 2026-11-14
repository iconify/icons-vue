<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vz8umibvp"/><path class="axe3h_bft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:birthday-hat" /></template>
<style>
.axe3h_bft {
  d: path("M9.75 4.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM8 15l2 2l2-2l2 2l2-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vz8umibvp {
  d: path("M5.5 20L12 6.5L18.5 20c-4.5 1.5-8.5 1.5-13 0Z");
}

</style>
