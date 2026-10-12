<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="te9a3ab3j"/><path class="saz3f4b1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chicken-coop-sharp" /></template>
<style>
.saz3f4b1z {
  d: path("M7.75 17.5v-4h3.5v4Zm-1.25 0v3.75m11-3.75v3.75m-6.25-3.75L15 21.25");
}

.te9a3ab3j {
  d: path("M4.75 16.7v-6.45l.61-.52l6.03-5.21L12 4l.61.52l6.03 5.21l.61.52v7.25H4.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
