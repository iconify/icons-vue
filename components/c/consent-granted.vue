<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n5cg660mb"/><path class="eedpwlb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consent-granted" /></template>
<style>
.eedpwlb9y {
  d: path("M8.5 7.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1.5 8c0-1.75 1.75-2.75 4-2.75c1.605 0 2.955.509 3.598 1.435M14.75 18l2 2L21 15.75");
}

.n5cg660mb {
  d: path("M14.3 21.5H4.5v-19h15v10.8m0 7.9v.3h-.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
