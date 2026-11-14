<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f66btg_nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blend-tool" /></template>
<style>
.f66btg_nw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 18.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM9.5 9.5h5v5h-5Zm6.25-7h5.75v5.75h-5.75Z");
}

</style>
