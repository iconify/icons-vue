<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydn_u2bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:badminton-sharp" /></template>
<style>
.ydn_u2bnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.25h11.25l-.36 1.2l-2.78 9.1l-.36 1.2h-5.5l-.36-1.2l-2.78-9.1l-.36-1.2zm3 2.5l.75 6.5M14 5.75l-.75 6.5m-4 5h5.5v1.25a2.75 2.75 0 0 1-5.5 0Z");
}

</style>
