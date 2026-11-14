<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i36fplpdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gym-selfie" /></template>
<style>
.i36fplpdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h11v19h-11Zm4.25 2.75h2.5m-.896 3.361l-3.536 3.535m7.071 0l-3.535 3.536m-1.768-5.303l3.535 3.535");
}

</style>
