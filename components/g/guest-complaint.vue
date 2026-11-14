<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr605xbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guest-complaint" /></template>
<style>
.zr605xbil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6A2.5 2.5 0 0 1 6 3.5h12A2.5 2.5 0 0 1 20.5 6v8.5A2.5 2.5 0 0 1 18 17H8.5l-5 4Zm8.5.5v4m0 3h.01");
}

</style>
