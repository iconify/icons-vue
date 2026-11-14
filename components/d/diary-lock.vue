<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x3iy_xbqn"/><path class="u35q9pbch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diary-lock" /></template>
<style>
.u35q9pbch {
  d: path("M10.75 11.5h5.5V16h-5.5Zm1.25 0V10a1.5 1.5 0 0 1 3 0v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x3iy_xbqn {
  d: path("M4.5 2.5h15v19h-15Zm3 0v19");
}

</style>
