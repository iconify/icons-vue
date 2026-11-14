<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="koe1hgz_k"/><path class="pj8y1lwts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:geothermal-plant" /></template>
<style>
.koe1hgz_k {
  d: path("M2.5 21h19M5 21c2-4 2.5-7 1.5-10.5h7C12.5 14 13 17 15 21M10 7.75C8.75 6.5 8.75 5.5 10 4.25S11.25 2.5 10 2");
}

.pj8y1lwts {
  d: path("M12.75 15.5h5.75V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
