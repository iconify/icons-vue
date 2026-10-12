<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wq9fgotrz"/><path class="g3yryacrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blood-drop-type-sharp" /></template>
<style>
.g3yryacrv {
  d: path("M8.75 17.5L11 11.75l2.25 5.75m-3.65-2h2.8m6.6-12v4m-2-2h4");
}

.wq9fgotrz {
  d: path("M11 2.75C14 6.5 17.25 10 17.25 14a6.25 6.25 0 0 1-12.5 0C4.75 10 8 6.5 11 2.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
