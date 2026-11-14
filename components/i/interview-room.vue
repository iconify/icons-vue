<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yp9hm2bdi"/><path class="o0ng2bc4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interview-room" /></template>
<style>
.o0ng2bc4c {
  d: path("M8.75 5.25h2.5v7h-2.5Zm6.5 7.25h.01m-6.51 2.75h6.5v3.5h-6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yp9hm2bdi {
  d: path("M6 2.5h12v19H6Zm-3.5 19h19");
}

</style>
