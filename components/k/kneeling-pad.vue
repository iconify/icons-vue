<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj20akb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kneeling-pad" /></template>
<style>
.rj20akb4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6.5C8 5 16 5 20 6.5c1.5 1.5 1.5 6.5 0 8c-4 1.5-12 1.5-16 0C2.5 13 2.5 8 4 6.5m-1.5 12h19m-15-8h11");
}

</style>
