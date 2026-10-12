<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tc_hg3b7j"/><path class="d-zgbzbgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:electric-motor-sharp" /></template>
<style>
.d-zgbzbgn {
  d: path("m10.5 8.75l-2 3.5h3l-2 3.5M16.25 12h5m-14.5 5.75v2.5m6.5-2.5v2.5");
}

.tc_hg3b7j {
  d: path("M3.75 6.25h12.5v11.5H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
