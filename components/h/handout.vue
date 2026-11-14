<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu8rtizmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:handout" /></template>
<style>
.fu8rtizmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h12.5v19H3Zm3 4h6.5m-6.5 4h6.5M6 14h3.5M6 17.5h5m1.5-3.5h9m-3-3l3 3l-3 3");
}

</style>
