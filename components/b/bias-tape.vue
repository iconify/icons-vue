<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pyqsp1igo"/><path class="w_6zwlbld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bias-tape" /></template>
<style>
.pyqsp1igo {
  d: path("M9 15.5a6.5 6.5 0 1 1 0-13a6.5 6.5 0 0 1 0 13h8.5l3.5 5h-8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_6zwlbld {
  d: path("M6.5 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
