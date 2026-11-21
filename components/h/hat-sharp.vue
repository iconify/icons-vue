<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwwq7ecgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hat-sharp" /></template>
<style>
.xwwq7ecgw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 13L2 14C2 16.7614 4.2386 19 7 19L17 19C19.7614 19 22 16.7614 22 14L22 13M5.4575 18.7544L5.5 18.5L7.7547 5L9.8571 5L12 6.5001L14.1429 5L16.2453 5L18.5 18.5L18.5425 18.7544M6.4206 13L6.5715 13L17.4285 13L17.5793 13");
}

</style>
