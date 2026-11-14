<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka_x2k8rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:design-token-spacing" /></template>
<style>
.ka_x2k8rq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3.5za2 2 0 0 1 2 2v13a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-13a2 2 0 0 1 2-2m15 0za2 2 0 0 1 2 2v13a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-13a2 2 0 0 1 2-2M11.25 10l-2 2l2 2m-2-2h5.5m-2-2l2 2l-2 2");
}

</style>
