<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qg6qik-7w"/><path class="zwegi9bzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:checkout-address" /></template>
<style>
.qg6qik-7w {
  d: path("M13.56 20.5H4v-10l8-7l8 7v.84");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwegi9bzi {
  d: path("M16 7V4h2v4.75m0 12.75c-1.75-1.75-3-3.25-3-4.75a3 3 0 0 1 6 0c0 1.5-1.25 3-3 4.75Z");
}

</style>
