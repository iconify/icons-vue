<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htkz26b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-right-sharp" /></template>
<style>
.htkz26b2v {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 10L6 21M2.7071 17.7071L6 21L9.2929 17.7071M10 6L21 6M17.7071 9.2929L21 6L17.7071 2.7071M21 12L21 15.3333M21 17.3333L21 21L17.3333 21M15.3333 21L12 21");
}

</style>
