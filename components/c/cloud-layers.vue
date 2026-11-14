<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw9ilc6ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloud-layers" /></template>
<style>
.bw9ilc6ib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7a1.5 1.5 0 0 1 0-3h2.5a3 3 0 0 1 5 0H16a1.5 1.5 0 0 1 0 3Zm3 7.25a1.5 1.5 0 0 1 0-3h4a3 3 0 0 1 5 0h2a1.5 1.5 0 0 1 0 3ZM4 21.5a1.5 1.5 0 0 1 0-3h3a3 3 0 0 1 5 0h3a1.5 1.5 0 0 1 0 3Z");
}

</style>
