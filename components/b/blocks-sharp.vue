<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp604hfeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:blocks-sharp" /></template>
<style>
.mp604hfeq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5L11 5L11 13L19 13L19 21L3 21L3 5ZM3 13L11 13M11 13L11 21M15 3L21 3L21 9L15 9L15 3Z");
}

</style>
