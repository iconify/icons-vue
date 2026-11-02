<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k79sg0bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-duotone-sharp" /></template>
<style>
.k79sg0bpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 11l-2 2a4.243 4.243 0 0 0 6 6l2-2m4-4l2-2a4.243 4.243 0 0 0-6-6l-2 2m-3 9l8-8");
}

</style>
