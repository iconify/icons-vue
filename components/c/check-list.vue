<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvh4fdbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:check-list" /></template>
<style>
.kvh4fdbvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 6l1.75 1.75L8 4.5M3 13l1.75 1.75L8 11.5M11 6h10m-10 7h10M3 17.5h4.5v4H3Zm8 2h10");
}

</style>
