<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cxmd3fufi"/><path class="o7gia1o_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-screw" /></template>
<style>
.cxmd3fufi {
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.o7gia1o_i {
  d: path("M10 8.5h4v13h-4Zm-2.5 5l9-2m-9 6l9-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
