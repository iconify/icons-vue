<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grapi_-bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:article-heart" /></template>
<style>
.grapi_-bv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.1 20H3V2h14v10.7M6.5 6.5h7m-7 4h7m-7 4H10m8.5 7l-3-3a1.75 1.75 0 0 1 3-2.25a1.75 1.75 0 0 1 3 2.25Z");
}

</style>
