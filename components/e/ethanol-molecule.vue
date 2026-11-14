<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oow5hhb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ethanol-molecule" /></template>
<style>
.oow5hhb2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM8 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5-5.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-11.25 3.5l2-2.5m3.5.25l1.5 2M17 13l1.75-2");
}

</style>
