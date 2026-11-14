<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a4stnrb-k"/><path class="gbg0nnujf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lighting-controller" /></template>
<style>
.a4stnrb-k {
  d: path("M6 21.5v-14a5 5 0 0 1 5-5h4.75v1");
}

.gbg0nnujf {
  d: path("M12 7.25a3.75 3.75 0 0 1 7.5 0ZM3.5 21.5h5m3-7.5h9v7.5h-9Zm2.75 3.75h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
