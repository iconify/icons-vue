<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og0k6xbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heavy-stapler-sharp" /></template>
<style>
.og0k6xbaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.24 8.31l13.52-2.12L19 6l1 .75l1 .75v4H3v-3zM19.5 11.5V15M3 15h18v4H3z");
}

</style>
