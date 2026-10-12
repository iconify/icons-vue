<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="i66ibbo0w"/><path class="yrsxudblh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corner-left-up-sharp" /></template>
<style>
.i66ibbo0w {
  d: path("M19.75 19.75H9.25v-15");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrsxudblh {
  d: path("M13 8.5L9.25 4.75L5.5 8.5");
}

</style>
