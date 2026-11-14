<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-8281rfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-beckon" /></template>
<style>
.s-8281rfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21.5v-2.75l-3.75-4a1.75 1.75 0 0 1 2.5-2.5L9 13.5v-7a2.5 2.5 0 0 1 5 0V9m-1 3h3.5a2.5 2.5 0 0 1 2.5 2.5v2a5 5 0 0 1-3 4.5v.5");
}

</style>
