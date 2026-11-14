<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d3zg4wa2e"/><path class="uztqqg1zk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flexbox" /></template>
<style>
.d3zg4wa2e {
  d: path("M2.5 4.5h19v15h-19Zm4 0v15m11-15v15M9.25 12h5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uztqqg1zk {
  d: path("M11 10.25L9.25 12L11 13.75m2-3.5L14.75 12L13 13.75");
}

</style>
