<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn_kot9_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charity-auction" /></template>
<style>
.yn_kot9_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.091 2.02l3.889 3.889l-7.071 7.071L3.02 9.091ZM10.5 9.5l3.677 3.677M12.5 19.2v2.3H3v-4h8.9m6.1 3.75L15 18a1.9 1.9 0 0 1 3-2.25A1.9 1.9 0 0 1 21 18Z");
}

</style>
