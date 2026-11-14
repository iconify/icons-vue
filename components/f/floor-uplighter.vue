<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmm8bsb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:floor-uplighter" /></template>
<style>
.cmm8bsb2f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.5h11Q17 11 12 11T6.5 7.5ZM12 11v10m-3.5 0h7M12 2.5v2.25m-3.5 0l-1-2m8 2l1-2");
}

</style>
