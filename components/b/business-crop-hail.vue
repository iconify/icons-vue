<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpxz-4frp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:business-crop-hail" /></template>
<style>
.fpxz-4frp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V8m0 9c-2 .5-4-1-4-3.25c2-.25 3.75 1.25 4 3.25m0 0c2 .5 4-1 4-3.25c-2-.25-3.75 1.25-4 3.25m0-6c-2 .5-4-1-4-3.25C10 7.5 11.75 9 12 11m0 0c2 .5 4-1 4-3.25C14 7.5 12.25 9 12 11m-1.5-5.5a1.5 2.75 0 1 0 3 0a1.5 2.75 0 1 0-3 0M3 21h18M5 4h.01M19 4h.01m.49 6h.01");
}

</style>
