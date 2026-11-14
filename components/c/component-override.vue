<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l2lrl-btw"/><path class="b_jbgfyxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:component-override" /></template>
<style>
.b_jbgfyxk {
  d: path("m13.5 13.5l7 2.75l-3 1.25l-1.25 3Z");
}

.l2lrl-btw {
  d: path("M11.782 16.718L10.5 18L3 10.5L10.5 3l7.5 7.5l-1.268 1.268");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
