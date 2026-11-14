<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g8lhtrb2i"/><path class="xj1-hmhab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fibonacci-spiral" /></template>
<style>
.g8lhtrb2i {
  d: path("M2.25 6h19.5v12H2.25Zm12 0v12m0-4.5h7.5m-4.5 0V18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xj1-hmhab {
  d: path("M2.25 18a12 12 0 0 1 12-12a7.5 7.5 0 0 1 7.5 7.5a4.5 4.5 0 0 1-4.5 4.5");
}

</style>
