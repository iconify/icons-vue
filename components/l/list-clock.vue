<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c_arb62lc"/><path class="v7xutcx-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:list-clock" /></template>
<style>
.c_arb62lc {
  d: path("M4 5.5h.01M8 5.5h12.5M4 11.5h.01m3.99 0h12.5M4 17.5h.01m3.99 0h4m3 .75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7xutcx-f {
  d: path("M18 17v1.25l1 .5");
}

</style>
