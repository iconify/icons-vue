<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gkupb8puy"/><path class="aezb2i3kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:good-bacteria" /></template>
<style>
.aezb2i3kc {
  d: path("M6.5 7.5c1.5-1.25 2 1.25 3.5 0s2 1.25 3.5 0M18 15v6m-3-3h6");
}

.gkupb8puy {
  d: path("M4.5 3.5h11a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
