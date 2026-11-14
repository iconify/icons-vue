<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a-me-5h7q"/><path class="o4nzb2bzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:checkride" /></template>
<style>
.a-me-5h7q {
  d: path("M13.9 21.5H2.5V4H18v7.7");
}

.o4nzb2bzr {
  d: path("M8 2.5h5V5H8ZM5.5 9L7 10.5L9.5 8m-4 6.25l1.5 1.5l2.5-2.5m2.5-4h3.25M12 14.5h3.25M5.5 18.75h6.3m6.7-4.25v7m-3-2.5l3-2.25l3 2.25M17 21.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
