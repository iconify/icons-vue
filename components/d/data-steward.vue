<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s00oxjest"/><path class="x216ecbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-steward" /></template>
<style>
.s00oxjest {
  d: path("M12.672 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.49 0 .963.039M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11 6.75l3.25 1.25V18c0 1.9-1.35 3.1-3.25 3.75c-1.9-.65-3.25-1.85-3.25-3.75v-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x216ecbyc {
  d: path("m16.5 18l1 1l2-2");
}

</style>
