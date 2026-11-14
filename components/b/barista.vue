<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mnttcab_z"/><path class="ndj8bdcuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barista" /></template>
<style>
.mnttcab_z {
  d: path("M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3 21.5c0-4 3.25-7 7.5-7q.863.002 1.662.159");
}

.ndj8bdcuq {
  d: path("M7.25 21.5v-3.25h4.95m.05 1.15v2.1m2.75-6h5v3.75a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1-2.5-2.5Zm5 1a1.5 1.5 0 0 1 0 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
