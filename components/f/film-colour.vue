<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqkjl_eos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:film-colour" /></template>
<style>
.xqkjl_eos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19m-19 16h19M3.5 7H5m3.25 0h1.5m4.5 0h1.5M19 7h1.5m-17 10H5m3.25 0h1.5m4.5 0h1.5M19 17h1.5m-18-5A2.25 2.25 0 1 0 7 12a2.25 2.25 0 1 0-4.5 0Zm7.25 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM17 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

</style>
