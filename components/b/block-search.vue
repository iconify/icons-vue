<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ixk48ebiq"/><path class="fj-offwbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:block-search" /></template>
<style>
.fj-offwbh {
  d: path("M3.5 7.25L12 12l8.5-4.75M12 12v3.5m0 3.5v2.5m2.5-4.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm4.75 2l2 2");
}

.ixk48ebiq {
  d: path("M13.112 20.878L12 21.5l-8.5-4.75v-9.5L12 2.5l8.5 4.75v5.463");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
