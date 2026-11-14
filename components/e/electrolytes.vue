<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xdb5c4bgn"/><path class="hx65q2bpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electrolytes" /></template>
<style>
.hx65q2bpd {
  d: path("m12.75 8l-3 5h4.5L11 18.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdb5c4bgn {
  d: path("M12 2.5s-7 7.5-7 12a7 7 0 0 0 14 0c0-4.5-7-12-7-12Z");
}

</style>
