<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvk2_jg0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-aisle" /></template>
<style>
.vvk2_jg0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5v19m16-19v19M4 11h16M4 19h16M7 11V8a2 2 0 0 1 2-2V4h2v2a2 2 0 0 1 2 2v3m-2 3h6v5h-6Z");
}

</style>
