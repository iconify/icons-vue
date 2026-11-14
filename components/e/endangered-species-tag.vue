<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex66kccto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:endangered-species-tag" /></template>
<style>
.ex66kccto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.733 11.956q.14-.22.267-.456C18 6 10.5 6 7.5 11.5L3 7.5v8l4.5-4c1.676 3.073 4.757 4.429 7.673 4.068M16.5 10.5h.01M18 14.75v3.5M18 21h.01");
}

</style>
