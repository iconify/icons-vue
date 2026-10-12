<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hdv5-jxat"/><path class="pmf4mcnkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:elevation-drawing-sharp" /></template>
<style>
.hdv5-jxat {
  d: path("M2.75 2.75h18.5v18.5H2.75zM5.5 17.5h13");
}

.pmf4mcnkp {
  d: path("M7 17.5v-6l5-4.25l5 4.25v6m-6.5 0V14h3v3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
