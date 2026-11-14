<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rhc09acov"/><path class="n2tkynbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charango" /></template>
<style>
.n2tkynbtv {
  d: path("M10.25 15.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.rhc09acov {
  d: path("M12 7.25c2.25 0 3.5 1.5 3.25 3.5c-.25 1.25-.5 1.75.5 2.75C17 14.75 17 16 17 17c0 2.75-2.25 4.5-5 4.5S7 19.75 7 17c0-1 0-2.25 1.25-3.5c1-1 .75-1.5.5-2.75c-.25-2 1-3.5 3.25-3.5Zm0 0V5m-1.75 0h3.5l-.5-2.5h-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
