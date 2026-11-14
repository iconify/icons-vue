<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jrqp-1qxl"/><path class="o-ixaubjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:award-trophy" /></template>
<style>
.jrqp-1qxl {
  d: path("M7 3.5h10V9A5 5 0 0 1 7 9Zm1 14h8v4H8Z");
}

.o-ixaubjk {
  d: path("M7 5.5H5a2.5 2.5 0 0 0 0 5h2.25m9.75-5h2a2.5 2.5 0 0 1 0 5h-2.25M12 14v3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
