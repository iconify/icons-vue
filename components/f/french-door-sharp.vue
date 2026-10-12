<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kr3nqqjwv"/><path class="wgqz0rmnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:french-door-sharp" /></template>
<style>
.kr3nqqjwv {
  d: path("M2.75 2.75h18.5v18.5H2.75zm9.25 0v18.5");
}

.wgqz0rmnm {
  d: path("M5.75 5.75H9v8H5.75Zm9.25 0h3.25v8H15Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
