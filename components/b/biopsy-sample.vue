<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pwim8xn9h"/><path class="g07tbx4cq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biopsy-sample" /></template>
<style>
.g07tbx4cq {
  fill: currentColor;
  d: path("M9.5 16c0-1.5 1.25-2.5 2.75-2.25s2.5 1.5 2 3s-2.25 2-3.5 1.5C10 17.75 9.5 17 9.5 16Z");
}

.pwim8xn9h {
  d: path("M5 3h14v3.5H5Zm1 3.5v13c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2v-13m-12 4h12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
