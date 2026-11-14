<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4h7y9xxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:artist-hand-model" /></template>
<style>
.i4h7y9xxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 10h9v6H9Zm1.75 0V4m2.75 6V2.5m2.75 7.5V4M9 13L6 9.5m7.5 6.5v5.5m-4 0h8");
}

</style>
