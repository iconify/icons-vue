<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu-xb-gdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:decimal-increase" /></template>
<style>
.wu-xb-gdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5a2 2 0 1 1 4 0v2a2 2 0 1 1-4 0Zm8 0a2 2 0 1 1 4 0v2a2 2 0 1 1-4 0ZM3 9h.01M18 21l3-3l-3-3m3 3H3");
}

</style>
