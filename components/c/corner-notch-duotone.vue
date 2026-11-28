<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wljt63bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-notch-duotone" /></template>
<style>
.wljt63bsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L14 3C14.5523 3 15 3.4477 15 4L15 8C15 8.5523 15.4477 9 16 9L20 9C20.5523 9 21 9.4477 21 10L21 21");
}

</style>
