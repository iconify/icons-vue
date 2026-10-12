<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h03djckqv"/><path class="gv2owr6mz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:auto-start-stop-sharp" /></template>
<style>
.gv2owr6mz {
  d: path("m9 16l3-8l3 8m-4.75-2.75h3.5");
}

.h03djckqv {
  d: path("M17.5 5.5a8.5 8.5 0 1 1-11 0m-3-.25l3 .25l-.25 3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
