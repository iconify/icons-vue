<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dys4ds_xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cap-sharp" /></template>
<style>
.dys4ds_xw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 14.75V13a7 7 0 0 1 14 0v1.75Zm7-7.25v7m-7 4v-1.25h17.5v3.5H3.75V19.5Z");
}

</style>
