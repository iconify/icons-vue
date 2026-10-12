<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4r400b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:composition-grid" /></template>
<style>
.v4r400b4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.25v-1.5a2 2 0 0 1 2-2h1.5m11.5 0h1.5a2 2 0 0 1 2 2v1.5m0 5.5v1.5a2 2 0 0 1-2 2h-1.5m-11.5 0h-1.5a2 2 0 0 1-2-2v-1.5m3.75 1l11-7.5m-11 0l3.5 5.12m7.5 2.38L14 10.63");
}

</style>
