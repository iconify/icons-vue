<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ngsyhfz1b"/><path class="b50kt7_dj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:campus-sharp" /></template>
<style>
.b50kt7_dj {
  d: path("M10.5 21.25v-5h3v5");
}

.ngsyhfz1b {
  d: path("M2.75 11.25H8v10H2.75zm13.25 0h5.25v10H16zm-8 9V8.5l.73-.68l2.54-2.39l.73-.68l.73.68l2.54 2.39l.73.68v12.75H8zM5.25 14.5v3.25m13.5-3.25v3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
