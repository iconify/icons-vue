<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bcaloab6y"/><path class="i24hlxbgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boarding-position" /></template>
<style>
.bcaloab6y {
  d: path("M10 15H4.5a2 2 0 0 1-2-2V5.5a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2V13a2 2 0 0 1-2 2H14m-4 0V7h4v8");
}

.i24hlxbgp {
  d: path("M3.5 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm14 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM2.5 21h19m-12-3h5v3h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
