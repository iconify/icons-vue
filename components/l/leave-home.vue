<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eajkh3y6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leave-home" /></template>
<style>
.eajkh3y6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 18.5V20H3v-9l5.5-5l5.5 5v1.5m-3.5 3h11m-2.25-2.25l2.25 2.25l-2.25 2.25");
}

</style>
