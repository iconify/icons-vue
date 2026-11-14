<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yktagpbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cosmetic-pump" /></template>
<style>
.yktagpbzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.875 10.5h2.25a4.375 4.375 0 0 1 4.375 4.375v1.75A4.375 4.375 0 0 1 13.125 21h-2.25A4.375 4.375 0 0 1 6.5 16.625v-1.75a4.375 4.375 0 0 1 4.375-4.375m-.875 0V8h4v2.5M12 8V4.5h4M9.5 15.75h5");
}

</style>
