<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcw58tbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:component-broken" /></template>
<style>
.fcw58tbcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l3.25 3.25L12 9L8.75 5.75ZM5.75 8.75L9 12l-3.25 3.25L2.5 12Zm12.5 0L21.5 12l-3.25 3.25L15 12Zm-3.638 6.696l1.942 4.166l-4.166 1.942l-1.942-4.166Z");
}

</style>
