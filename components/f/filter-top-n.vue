<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnm__dr0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:filter-top-n" /></template>
<style>
.gnm__dr0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.732 19.366L8 17.5V11L2.5 3.5h15L12 11v4.499m2.5 6.001v-3.25h2.25v-3.5h2.5V17h2.25v4.5Z");
}

</style>
