<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h0nhg13nw"/><path class="yirdlgj3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:background-job" /></template>
<style>
.h0nhg13nw {
  d: path("M13.462 15.769L10 17.5l-7.5-3.75v-7.5L10 2.5l7.5 3.75v6.415");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yirdlgj3y {
  d: path("M2.5 6.25L10 10l7.5-3.75M10 10v7.5m5 3.5l5.25-5.25m-4-.25h4.25v4.25");
}

</style>
