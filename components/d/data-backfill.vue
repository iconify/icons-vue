<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oq2xexblz"/><path class="osqky4cvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-backfill" /></template>
<style>
.oq2xexblz {
  d: path("M20.5 6.5H4m3-3l-3 3l3 3M2.5 13H7v4.5H2.5Zm7.25 0h4.5v4.5h-4.5ZM17 13h4.5v4.5H17Z");
}

.osqky4cvz {
  fill: currentColor;
  d: path("M3.5 15.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm7.25 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
