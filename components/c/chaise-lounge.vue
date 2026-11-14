<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt56ibbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chaise-lounge" /></template>
<style>
.pt56ibbgz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13.5h10.5c2 0 3-6.5 5.25-7c1.5-.25 2.25.75 2.25 2c0 3.5-2 8.5-5 8.5H4.5A1.5 1.5 0 0 1 3 15.5ZM5 17v2.5M16 17v2.5");
}

</style>
