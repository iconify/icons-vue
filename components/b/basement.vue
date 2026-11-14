<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="llmeiccki"/><path class="suf5t7bvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basement" /></template>
<style>
.llmeiccki {
  d: path("m5 8.5l7-6l7 6V13H5ZM2.5 13h19");
}

.suf5t7bvl {
  d: path("M10.5 13v-3h3v3m-8 2.75h13v5.75h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
