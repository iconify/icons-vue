<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5wzn9b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:birthday-crown" /></template>
<style>
.o5wzn9b0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 9l4 3.5L12 7l4 5.5L20 9l-1.25 10H5.25Zm8-5h.01M3.25 6h.01m17.49 0h.01M6 15.75h12");
}

</style>
