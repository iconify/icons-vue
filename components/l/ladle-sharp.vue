<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbn1trb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ladle-sharp" /></template>
<style>
.wbn1trb-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25h10a5 5 0 0 1-10 0Zm2 2.25h6m2-2.25L17.9 5.2a1.5 1.5 0 0 1 2.55 1.6");
}

</style>
