<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="fwnlhrbgy"/><path class="i4-v1pm5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dragonfly-sharp" /></template>
<style>
.fwnlhrbgy {
  cx: 12px;
  cy: 5.5px;
  r: 2.25px;
}

.i4-v1pm5j {
  d: path("M12 9.5v11.75m-1.5-12c-2-1.5-5.25-2.25-6.75-1.5c-1.25.75-.75 2.5 1.25 3c1.75.5 3.75.25 5.5-1.5Zm3 0c2-1.5 5.25-2.25 6.75-1.5c1.25.75.75 2.5-1.25 3c-1.75.5-3.75.25-5.5-1.5Zm-3 2.75c-2 .75-4 2-4.75 3.5c-.6 1.25.4 2.25 1.9 1.6c1.5-.6 2.6-2.35 2.85-5.1Zm3 0c2 .75 4 2 4.75 3.5c.6 1.25-.4 2.25-1.9 1.6c-1.5-.6-2.6-2.35-2.85-5.1Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
