<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq-z0xq9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:herb-sprig" /></template>
<style>
.vq-z0xq9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V9m0 0c-2-1.5-2-4 0-6c2 2 2 4.5 0 6m0 5c-2-3-5-4-7.5-3.5C5 13 8 15 12 14m0 0c2-3 5-4 7.5-3.5C19 13 16 15 12 14");
}

</style>
