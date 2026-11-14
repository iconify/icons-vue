<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq_r3vbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-pin" /></template>
<style>
.aq_r3vbkv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.9 19H2.5V5h19v7.8m-19-3.3h19m-19 0h19M6 15h2.5m9.5 0v6m-2.5-4.5l5 3m-5 0l5-3");
}

</style>
