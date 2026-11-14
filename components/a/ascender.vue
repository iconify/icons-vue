<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct3cf2v9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ascender" /></template>
<style>
.ct3cf2v9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3v18m0-6a4.5 4.5 0 0 1 9 0v6M2.5 10.5h19m-2-2.75V3m-2 2l2-2l2 2");
}

</style>
