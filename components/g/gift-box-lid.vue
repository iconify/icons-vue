<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq4efvo8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-box-lid" /></template>
<style>
.yq4efvo8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11.5h16v10H4ZM2.34 6.176l18.712-3.299l.608 3.447L2.948 9.623ZM12 11.5v10m-.304-16.973l.608 3.446");
}

</style>
