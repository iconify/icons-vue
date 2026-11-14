<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lj_uv46cg"/><path class="zitcenpah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calm-corner" /></template>
<style>
.lj_uv46cg {
  d: path("M4 19c-1.75 0-2-2-1.5-4c1-5 4-9 8-9.5C12 5.25 12.5 7 14 7s2.5-1.5 4-.5c2.5 2 3.5 6 3.5 9.5c0 2-1 3-2.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zitcenpah {
  d: path("M6.5 13c3-1.75 7-1.5 10 1");
}

</style>
