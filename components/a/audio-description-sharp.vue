<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8ochl6_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audio-description-sharp" /></template>
<style>
.e8ochl6_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17.75L6 6.75l3.25 11M4 14h4m3.25-7.25v11h1.5a5.5 5.5 0 0 0 0-11Zm8.5 1.5l1.5 1.5v4.5l-1.5 1.5");
}

</style>
