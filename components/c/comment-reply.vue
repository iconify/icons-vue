<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hpkep8bsv"/><path class="umf7udl4c"/><path class="gk_cikbbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:comment-reply" /></template>
<style>
.gk_cikbbr {
  d: path("M10.75 9.25L8.5 11.5l2.25 2.25");
}

.hpkep8bsv {
  d: path("m7.5 19.5l-3.5 1L5 17a8.5 8.5 0 1 1 2.5 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umf7udl4c {
  d: path("M15.5 15v-1a2.5 2.5 0 0 0-2.5-2.5H8.5");
}

</style>
