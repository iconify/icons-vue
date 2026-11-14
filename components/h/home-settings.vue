<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pb3m6g_mh"/><path class="e7obq2bcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-settings" /></template>
<style>
.e7obq2bcb {
  d: path("m17.233 15.359l.103-1.05h1.328l.103 1.05l1.136.656l.961-.435l.664 1.15l-.857.614v1.312l.857.614l-.664 1.15l-.961-.435l-1.136.656l-.103 1.05h-1.328l-.103-1.05l-1.136-.656l-.961.435l-.664-1.15l.857-.614v-1.312l-.857-.614l.664-1.15l.961.435Z");
}

.pb3m6g_mh {
  d: path("M11.944 20.5H3.5v-10L12 3.25l8.5 7.25v1.056");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
