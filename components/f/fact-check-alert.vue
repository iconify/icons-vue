<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bf0ou6e2t"/><path class="f_51k3qye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fact-check-alert" /></template>
<style>
.bf0ou6e2t {
  d: path("M11.7 20.5H3.5v-18H19v7.3");
}

.f_51k3qye {
  d: path("m7 10l2.5 2.5l5-5m3.75 6.75l3.75 7h-7.5Zm0 4.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
