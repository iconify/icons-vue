<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fq1y8tbux"/><path class="k2o55zbcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:church-building-sharp" /></template>
<style>
.fq1y8tbux {
  d: path("M3.25 20.65V10l.37-.47l2.26-2.81l.37-.47l.37.47l2.26 2.81l.37.47v11.25h-6zm6 0V12.5l.46-.38l4.83-3.99l.46-.38l.46.38l4.83 3.99l.46.38v8.75H9.25zm-3-14.4v-3.5M5 4h2.5m-1.25 8v2.5M15 11.75v1.5");
}

.k2o55zbcc {
  d: path("M13.25 21.25v-4.5h3.5v4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
