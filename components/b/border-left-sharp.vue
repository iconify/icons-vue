<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw4n67bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:border-left-sharp" /></template>
<style>
.gw4n67bsq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 21L3 21L3 3L7 3M9.5 3L14.5 3M17 3L21 3L21 7M21 9.5L21 14.5M21 17L21 21L17 21M14.5 21L9.5 21");
}

</style>
