<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="icascg7wp"/><path class="i87yki_rm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:businesswoman" /></template>
<style>
.i87yki_rm {
  d: path("M9.75 8.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-.5 8.25l2.75 4l2.75-4");
}

.icascg7wp {
  d: path("M7 12.5V8a5 5 0 0 1 10 0v4.5m-13 9C4 18 7.5 16 12 16s8 2 8 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
