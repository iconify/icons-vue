<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gqzuiqmoh"/><path class="cu6umjb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-warehouse" /></template>
<style>
.cu6umjb_n {
  d: path("M7.5 12h9v8.5h-9Zm0 2.75h9m-9 2.75h9");
}

.gqzuiqmoh {
  d: path("m3.5 9.5l8.5-5l8.5 5v11h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
