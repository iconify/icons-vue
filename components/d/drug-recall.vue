<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h6eop-bov"/><path class="dtpudybos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drug-recall" /></template>
<style>
.dtpudybos {
  d: path("m14 2.5l-2 2l2 2M12 9v5m0 3.5h.01");
}

.h6eop-bov {
  d: path("M12 4.5A8.5 8.5 0 1 1 3.5 13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
