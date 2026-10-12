<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a2vb-rbpp"/><path class="te-hn4bgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-saw-sharp" /></template>
<style>
.a2vb-rbpp {
  d: path("m9.25 6.5l11.25 4.6l.753.329l-.003.821V16l-1.5 1.5l-1.5-1.5l-1.5 1.5l-1.5-1.5l-1.5 1.5l-1.5-1.5l-1.5 1.5l-1.5-1.5Z");
}

.te-hn4bgq {
  d: path("M2.75 5.5H9.5V18H2.75zM5.5 9.75V14");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
