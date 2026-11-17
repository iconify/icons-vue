<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxcxytboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooking-pot-round" /></template>
<style>
.yxcxytboa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 11v5a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4v-5M5 11h14M3 14h2m14 0h2M6 11a6.5 6.5 0 0 1 12 0m-6-4V4m-2 0h4");
}

</style>
