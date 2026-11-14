<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi4i3rhhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:first-last-service" /></template>
<style>
.gi4i3rhhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.75h19m-18.75 0a3.75 3.75 0 0 1 7.5 0m3.5 0a3.75 3.75 0 0 1 7.5 0M6.5 11V6.25m-2 2l2-2l2 2m9-2V11m-2-2l2 2l2-2");
}

</style>
