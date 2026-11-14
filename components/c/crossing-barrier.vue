<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nkis0bbjq"/><path class="jgtwt8jrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crossing-barrier" /></template>
<style>
.jgtwt8jrc {
  d: path("m8.375 11.659l9.576-8.034L20.2 6.306l-9.575 8.035Zm3.447-2.892l2.25 2.681m.814-5.252l2.25 2.681");
}

.nkis0bbjq {
  d: path("M5.5 11h4v10.5h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
