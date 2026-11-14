<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyak8ph9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:comb" /></template>
<style>
.xyak8ph9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.72 8.275l15.454-4.141l1.036 3.864l-15.455 4.141Zm2.967 3.346l2.07 7.727m.828-8.503l2.07 7.727m.827-8.504l2.071 7.728m.827-8.504l2.071 7.727m.827-8.504l2.07 7.728");
}

</style>
