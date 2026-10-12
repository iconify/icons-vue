<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="og70b5ofm"/><path class="ntwdvkb0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:danger-skull-sharp" /></template>
<style>
.ntwdvkb0i {
  d: path("M6.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-5.25 5.25h7.5m-5 0v3m2.5-3v3");
}

.og70b5ofm {
  d: path("M3 12a9 8 0 0 1 18 0v2.75l-3 2v3.5H6v-3.5l-3-2Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
