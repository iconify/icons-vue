<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="igv8f21ba"/><path class="msgwke1if"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bike-sharp" /></template>
<style>
.igv8f21ba {
  d: path("M6.25 12.5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7Zm11.5 0a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7Z");
}

.msgwke1if {
  d: path("m6.25 16l4.25-7l2 7h5.25M10.5 9l-.75-2.5m-1.5 0h3m6.5 9.5L15.5 8.5H18");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
