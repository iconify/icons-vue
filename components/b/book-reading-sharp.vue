<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vkicx9bty"/><circle class="wijmr5spd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:book-reading-sharp" /></template>
<style>
.vkicx9bty {
  d: path("M12 12.5L9.75 11h-7v8.5H6c2.5 0 4.5.4 6 1.25c1.5-.85 3.5-1.25 6-1.25h3.25V11h-7zm0 0v8.25");
}

.wijmr5spd {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
