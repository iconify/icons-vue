<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bruwbqbmb"/><path class="yz78o-bsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bnpl-split-four" /></template>
<style>
.bruwbqbmb {
  d: path("M10.5 5.5a8 8 0 1 0 8 8h-8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz78o-bsh {
  d: path("M13.25 2.75a8 8 0 0 1 8 8h-8ZM2.5 13.5h8m0 0v8");
}

</style>
