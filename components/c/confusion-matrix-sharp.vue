<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s6vwc8bde"/><path class="v1jljce8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:confusion-matrix-sharp" /></template>
<style>
.s6vwc8bde {
  d: path("M5.25 5.25h16v16h-16zm8 0v16m-8-8h16");
}

.v1jljce8r {
  d: path("M7.75 7.75h3v3h-3zm8 8h3v3h-3zm-13-8.25V11M7.5 2.75H11");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
