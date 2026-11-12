<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udmn-r9se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hearing-aid" /></template>
<style>
.udmn-r9se {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11a8 8 0 1 1 16 0c0 5-8 3-8 7a3 3 0 0 1-6 0m4-9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2v1l-2 1");
}

</style>
