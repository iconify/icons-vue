<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9-8s244i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:g-code" /></template>
<style>
.y9-8s244i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 7l-3.5 5L6 17M18 7l3.5 5l-3.5 5m-9-1c2.5 0 6.5-3.5 6.5-6c0-2.25-3.25-2.25-3.25.25C12.25 13 13.5 16 15 16");
}

</style>
