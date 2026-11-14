<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n0g7ilbbf"/><path class="kztpu9bdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keep-cool" /></template>
<style>
.kztpu9bdy {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v4.4m0 1.8v.6m0 1.8v1.4m6-7v7m-3-5.25l6 3.5m-6 0l6-3.5M16.5 15l1.5 1.5l1.5-1.5m-3 6l1.5-1.5l1.5 1.5");
}

.n0g7ilbbf {
  d: path("M12.562 21.203L12 21.5L3.5 17V7L12 2.5L20.5 7v4.682");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
