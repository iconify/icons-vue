<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aejgoyb1z"/><path class="kvf4_8_lo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-lost" /></template>
<style>
.aejgoyb1z {
  d: path("M13.7 19H2.5V5h19v9m0 4.7v.3h-.2M2.5 9.5h19m-19 0h19M6 15h2.5");
}

.kvf4_8_lo {
  d: path("M16.5 16.5c0-.9.7-1.5 1.5-1.5s1.5.6 1.5 1.5c0 1-1.5 1.1-1.5 2.25M18 21h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
