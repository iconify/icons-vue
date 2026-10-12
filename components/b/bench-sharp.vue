<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwktf8bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bench-sharp" /></template>
<style>
.mwktf8bkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 4.75v8m13.5-8v8m-15-6.5h16.5m-16.5 3.5h16.5m-17.5 3h18.5v3H2.75zm2.5 3v5.5m13.5-5.5v5.5");
}

</style>
