<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys5on0b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:line-height-tight" /></template>
<style>
.ys5on0b1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10h17m-17 4h17M12 2.5v4M9.75 4.25L12 6.5l2.25-2.25M12 21.5v-4m-2.25 2.25L12 17.5l2.25 2.25");
}

</style>
