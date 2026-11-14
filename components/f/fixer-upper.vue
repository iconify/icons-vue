<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wlif3hblo"/><path class="cmt-xh7vc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fixer-upper" /></template>
<style>
.cmt-xh7vc {
  d: path("M10.5 10.5h3v3h-3Zm3.75 7.5L18 14.5l3.75 3.5v3.75h-7.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wlif3hblo {
  d: path("M2.5 12L4 8.5h16l1.5 3.5m-10.1 9.5H2.5V12h14.1m2.8 0h2.1v2m-13-5.5v-3h7v3");
}

</style>
