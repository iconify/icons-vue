<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="ebi11agim"/><path class="mg1b7d1vw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:article-image" /></template>
<style>
.ebi11agim {
  d: path("M7.5 6h9v7.5h-9Z");
}

.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.mg1b7d1vw {
  d: path("m7.5 13.5l4-4l5 4m-9 4h9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
