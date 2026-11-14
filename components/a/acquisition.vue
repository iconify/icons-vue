<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhjhyf_jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:acquisition" /></template>
<style>
.jhjhyf_jr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5v-17A1.5 1.5 0 0 1 4.5 3h8A1.5 1.5 0 0 1 14 4.5v17M14 11h5.5a1.5 1.5 0 0 1 1.5 1.5v9m-18.5 0h19m-15-14h4m-4 4h4");
}

</style>
