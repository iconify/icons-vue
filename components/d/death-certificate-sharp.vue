<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h8jqndbwc"/><path class="jezyj860b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:death-certificate-sharp" /></template>
<style>
.h8jqndbwc {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.5 3.75h7.5");
}

.jezyj860b {
  d: path("m10 18l3.6-5.4a2.2 2.2 0 1 0-3.2 0L14 18");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
