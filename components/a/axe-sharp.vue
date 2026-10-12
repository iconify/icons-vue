<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6i-ci12s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:axe-sharp" /></template>
<style>
.q6i-ci12s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.75v18.5m0-17h5.5c4.25 0 7.75 3 8.75 7.75l.313 1.532l-1.563-.032h-13Z");
}

</style>
