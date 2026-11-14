<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="szzt4pbza"/><path class="wi0yisbjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donor-retention" /></template>
<style>
.szzt4pbza {
  d: path("M4 12.75a8 8 0 1 0 8-8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wi0yisbjf {
  d: path("m14 2.75l-2 2l2 2m-2 9.75l-3-3a2.12 2.12 0 0 1 3-3a2.12 2.12 0 0 1 3 3Z");
}

</style>
