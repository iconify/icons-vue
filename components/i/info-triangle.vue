<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djepoo9ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:info-triangle" /></template>
<style>
.djepoo9ww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.283 7.026l4.994 8.804a2.625 2.625 0 0 1-2.284 3.92H7.007a2.625 2.625 0 0 1-2.284-3.92l4.994-8.804a2.625 2.625 0 0 1 4.566 0M12 13.25v3.25m0-6.25h.01");
}

</style>
