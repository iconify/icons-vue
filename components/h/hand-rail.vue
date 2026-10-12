<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd96mpbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-rail" /></template>
<style>
.jd96mpbyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25h4.5v-4.5h4.5v-4.5h4.5v-4.5h5m-14 4v5m4.5-9.5v5m-7.5 2.5l12-12");
}

</style>
