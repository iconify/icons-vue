<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bjghabb4y"/><path class="qflyskbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-low-vision" /></template>
<style>
.bjghabb4y {
  d: path("M2.5 12C5 7.5 8.25 5.5 12 5.5s7 2 9.5 6.5M4 15l2.5 1.75m3.5 1.5h4m3.5-1.5L20 15");
}

.qflyskbix {
  d: path("M9.25 11.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
