<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5eegegjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-right-left-2" /></template>
<style>
.w5eegegjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 17L11.7396 17M15.8947 12L11.1367 16.6759C10.9544 16.8549 10.9544 17.1451 11.1367 17.3241L15.8947 22M2 7L12.2604 7M8.1053 12L12.8633 7.3241C13.0456 7.1451 13.0456 6.8549 12.8633 6.6759L8.1053 2");
}

</style>
