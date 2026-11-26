<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0f005k5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crane" /></template>
<style>
.z0f005k5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7L21 7M8 3L8 21M5 21L11 21M4 7L4 10M19 7L19 11M17 15L17 13C17 11.8954 17.8954 11 19 11C20.1046 11 21 11.8954 21 13L21 15");
}

</style>
