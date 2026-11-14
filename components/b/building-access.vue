<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xv1e-ac8i"/><path class="s1sc7yuit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:building-access" /></template>
<style>
.s1sc7yuit {
  d: path("M7.5 21.5V17h3v4.5M14 15h8v6h-8Zm0 2.25h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xv1e-ac8i {
  d: path("M11.2 21.5H3V6h3.5V3h5v3H15v6.2m-8-.7h.01m3.99 0h.01");
}

</style>
