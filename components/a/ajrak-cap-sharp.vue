<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jkycjqbxs"/><path class="wwct9wbvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ajrak-cap-sharp" /></template>
<style>
.jkycjqbxs {
  d: path("M3.75 15a8.25 8.25 0 0 1 16.5 0v3.75H3.75V17.5Zm.75-2h15");
}

.wwct9wbvc {
  d: path("m7 14.75l1.5 1.5l-1.5 1.5l-1.5-1.5Zm5 0l1.5 1.5l-1.5 1.5l-1.5-1.5Zm5 0l1.5 1.5l-1.5 1.5l-1.5-1.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
