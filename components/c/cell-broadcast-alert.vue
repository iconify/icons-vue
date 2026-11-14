<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypjdahb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cell-broadcast-alert" /></template>
<style>
.ypjdahb7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 5l7.5 13.5h-15Zm0 5.25v2.5m0 3h.01M3 8.75a9.5 9.5 0 0 0 0 6.5m18-6.5a9.5 9.5 0 0 1 0 6.5");
}

</style>
