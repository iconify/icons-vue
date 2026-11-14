<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c_11qvbvd"/><path class="yzqpbab2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cover-slip" /></template>
<style>
.c_11qvbvd {
  d: path("m2.5 18l5-12h14l-5 12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yzqpbab2j {
  d: path("m9.25 15l2.5-6h5.5l-2.5 6Z");
}

</style>
