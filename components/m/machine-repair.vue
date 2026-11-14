<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eelnzeh8c"/><path class="kdozwpbxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:machine-repair" /></template>
<style>
.eelnzeh8c {
  d: path("M13.588 15.665L11.5 16.5v2h-2v-2l-2.5-1L5.5 17L4 15.5L5.5 14l-1-2.5h-2v-2h2l1-2.5L4 5.5L5.5 4L7 5.5l2.5-1v-2h2v2l2.5 1L15.5 4L17 5.5L15.5 7l1 2.5h2v2h-2l-.371.928");
}

.kdozwpbxg {
  d: path("M8 10.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm13.25 6.25A2.5 2.5 0 1 1 19 14.5m-2 4.25L14.75 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
