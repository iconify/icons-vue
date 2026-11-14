<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yq312ub2n"/><path class="f3sxfe_qv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:college-fund" /></template>
<style>
.f3sxfe_qv {
  d: path("M4.5 12h-2v3h2m2-9.5L12 3.25l5.5 2.25l-5.5 2Zm1.25 6.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yq312ub2n {
  d: path("M4 13.5c0-3.5 3.5-6 8-6s8 2.5 8 6c0 2.25-1.25 4-3.5 5V21H14v-1.75c-.75.25-1.25.25-2 .25s-1.25 0-2-.25V21H7.5v-2.5c-2.25-1-3.5-2.75-3.5-5Z");
}

</style>
