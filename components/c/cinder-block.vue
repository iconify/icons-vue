<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rrrneebqb"/><path class="rq38klbjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinder-block" /></template>
<style>
.rq38klbjc {
  d: path("M5.5 7h4.75v4.75H5.5Zm8.25 0h4.75v4.75h-4.75Z");
}

.rrrneebqb {
  d: path("M2.5 4h19v16h-19Zm0 10.5h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
