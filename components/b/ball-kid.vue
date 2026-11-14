<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_6auqb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ball-kid" /></template>
<style>
.l_6auqb-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM3 21c0-3.5 2.25-5.5 5.5-5.5s5.5 2 5.5 5.5m2.5-2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-.25-8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
