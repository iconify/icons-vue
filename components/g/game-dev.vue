<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n8-i4o31r"/><path class="k3vcnrb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:game-dev" /></template>
<style>
.k3vcnrb_m {
  d: path("M10 7L7.5 9.5L10 12m4-5l2.5 2.5L14 12");
}

.n8-i4o31r {
  d: path("M4.5 4h15v11h-15Zm0 11l-2 4h19l-2-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
