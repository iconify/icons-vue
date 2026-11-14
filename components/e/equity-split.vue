<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yshkx3bnp"/><path class="gk4ff154h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:equity-split" /></template>
<style>
.gk4ff154h {
  d: path("M13.25 10.75v-8a8 8 0 0 1 8 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yshkx3bnp {
  d: path("M10.5 13.5v-8a8 8 0 1 0 8 8Z");
}

</style>
