<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu0ubjbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:infra-lint" /></template>
<style>
.bu0ubjbwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h18v4H3Zm16.6 10.75H3v-4h18v2.6m-9.5 6.85V20H3v-4h8.5v1.3m3.25.7l2 2L21 15.75");
}

</style>
