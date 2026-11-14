<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="axag_jbwy"/><path class="a7av5bb9s"/><path class="cl_d1f1yo"/><path class="hnfawxbfj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gps-approach" /></template>
<style>
.a7av5bb9s {
  d: path("m16.159 13.684l1.768 1.768l-2.475 2.475l-1.768-1.768Z");
}

.axag_jbwy {
  d: path("M14.622 21H3.5l5-18h5l2.192 7.173M11.25 7v3m0 3.5v1.2");
}

.cl_d1f1yo {
  d: path("m17.396 15.982l2.122 2.122l-1.414 1.414l-2.122-2.122Z");
}

.hnfawxbfj {
  d: path("m20.048 17.573l1.768 1.768l-2.475 2.475l-1.768-1.768Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
