<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qldxtbbhu"/><path class="nn025086t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drawing-pad" /></template>
<style>
.nn025086t {
  d: path("m8.25 16.75l1-2.75l5.25-5.25l1.75 2l-5 5.25Zm1-2.75l2 2");
}

.qldxtbbhu {
  d: path("M5 4.5h14v17H5Zm3.5-2v4m3.5-4v4m3.5-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
