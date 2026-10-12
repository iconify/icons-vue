<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gz6olcczg"/><path class="hak_f-7gb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dendrogram-sharp" /></template>
<style>
.gz6olcczg {
  d: path("M4.5 20.25V15H9v5.25M6.75 15V7.75H17V12m-5.25-4.25v-4.5");
}

.hak_f-7gb {
  d: path("M14.5 20.25V12h5v8.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
