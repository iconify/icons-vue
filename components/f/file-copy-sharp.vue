<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uycia5ppg"/><path class="xnph3kdsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-copy-sharp" /></template>
<style>
.uycia5ppg {
  d: path("M15.25 5.75h-8v15.5h13.5v-11Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xnph3kdsl {
  d: path("M4.25 15.75v-13h8.5m1.5 9.5v5m-2.5-2.5h5");
}

</style>
