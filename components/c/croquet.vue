<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldkm43but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:croquet" /></template>
<style>
.ldkm43but {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5h6V19h-6Zm3 0l3-12m0 14.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm8 4.75V12a2.5 2.5 0 0 1 5 0v9.5");
}

</style>
