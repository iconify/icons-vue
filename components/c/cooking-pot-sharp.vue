<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsd47gbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cooking-pot-sharp" /></template>
<style>
.qsd47gbsd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11L4 21L20 21L20 11M1 11L23 11M3 7L21 7M8 7L8 3L16 3L16 7");
}

</style>
