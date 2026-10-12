<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y4e18bnxi"/><path class="dfzyuab6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carabiner-sharp" /></template>
<style>
.dfzyuab6i {
  d: path("M15.25 13h2.5v4h-2.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4e18bnxi {
  d: path("M16.5 7.75c0-3-2.5-5-5.5-5H7.5v18.5H11c2.75 0 5.5-1.5 5.5-4.25m0-4v-2.25");
}

</style>
