<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1nnh-ueu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ionic-bond" /></template>
<style>
.s1nnh-ueu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm9.5 0a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Zm-2.5 0H12m-6-1.5v3M4.5 12h3m7 0H19");
}

</style>
