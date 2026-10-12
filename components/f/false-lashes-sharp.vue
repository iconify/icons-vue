<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t711vsihu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:false-lashes-sharp" /></template>
<style>
.t711vsihu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 15.6l-2.25-5.1m5.5 6.4L7 10m5 7.4v-7.15m3.75 6.65L17 10m2 5.6l2.25-5.1M3 14.5c5 4 13 4 18 0");
}

</style>
