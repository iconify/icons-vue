<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j9fpar72v"/><path class="gzn04_b1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-day-sharp" /></template>
<style>
.gzn04_b1i {
  d: path("M9.25 12.75h5.5v5h-5.5z");
}

.j9fpar72v {
  d: path("M3.75 5.25h16.5v15H3.75zm0 4.75h16.5M8 2.75v4.5m8-4.5v4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
