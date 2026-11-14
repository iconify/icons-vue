<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gv5ibwbdx"/><path class="cjw252mlc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-cat" /></template>
<style>
.cjw252mlc {
  d: path("M6 14h5.5v7H6Zm0 0l5.5 7m0-7L6 21m8.5-6.5l2 2h3l2-2V19c0 1.75-1.5 2.75-3.5 2.75s-3.5-1-3.5-2.75Z");
}

.gv5ibwbdx {
  d: path("M12.104 21H3V10l9-7l9 7v1.096");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
