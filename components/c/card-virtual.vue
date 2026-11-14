<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa7a56bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-virtual" /></template>
<style>
.oa7a56bbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9V7.5A2.5 2.5 0 0 1 5 5h3m8 0h3a2.5 2.5 0 0 1 2.5 2.5V9m0 6v1.5A2.5 2.5 0 0 1 19 19h-3m-8 0H5a2.5 2.5 0 0 1-2.5-2.5V15M11 5h2m-2 14h2M6 9.5h12");
}

</style>
