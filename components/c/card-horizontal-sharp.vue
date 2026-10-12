<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ohxdrbbbi"/><path class="kjqulp7dg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:card-horizontal-sharp" /></template>
<style>
.kjqulp7dg {
  d: path("M6.25 2.75h14v8.5H3.75v-8.5zm.75 12h10M7 18h6");
}

.ohxdrbbbi {
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
