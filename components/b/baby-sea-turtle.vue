<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jncc9cg6v"/><path class="n4230bbho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-sea-turtle" /></template>
<style>
.jncc9cg6v {
  d: path("M7 13a5 6 0 1 0 10 0a5 6 0 1 0-10 0Z");
}

.n4230bbho {
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM3 8.5Q4.5 8 7.75 10m.5 7Q6.5 19 5 19.5m16-11Q19.5 8 16.25 10m-.5 7q1.75 2 3.25 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
