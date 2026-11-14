<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gur12fbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bath-bubbles-kids" /></template>
<style>
.gur12fbkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5h19m-17 0v3a4 4 0 0 0 4 4h7a4 4 0 0 0 4-4v-3m-15-5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM10.25 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM16 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
