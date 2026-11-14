<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hh3a98bbv"/><path class="yzvzm9_hb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:badge-printer" /></template>
<style>
.hh3a98bbv {
  d: path("M2.5 3.5h19V15h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yzvzm9_hb {
  d: path("M8 11v9.5a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V11M6 11h12m-7.5 7h3");
}

</style>
