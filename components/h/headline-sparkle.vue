<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-ca5mbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headline-sparkle" /></template>
<style>
.o-ca5mbmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5H13v7H2.5Zm3 3.5H10m-7 8.5h18M3 20h11m4.75-16q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3Z");
}

</style>
