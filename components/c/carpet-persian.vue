<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zn_ck4bqc"/><path class="xjn0-0_4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carpet-persian" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xjn0-0_4s {
  d: path("M21.5 16.5q-2.75-.25-3 3M12 7.5l4.5 4.5l-4.5 4.5L7.5 12Zm0 4.5h.01");
}

.zn_ck4bqc {
  d: path("M4.5 4.5h15a2 2 0 0 1 2 2v10l-3 3h-14a2 2 0 0 1-2-2v-11a2 2 0 0 1 2-2Z");
}

</style>
