<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjg9bcbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laser-sharp" /></template>
<style>
.pjg9bcbwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8.25h9.5v2.25h2.25v3h-2.25v2.25H2.75v-7.5zm1 3.75h3.5m9.25 0h2.75m-2.5-4.25l2-1.25m-2 9.75l2 1.25");
}

</style>
