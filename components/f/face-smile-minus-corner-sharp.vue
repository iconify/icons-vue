<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoe65kboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-smile-minus-corner-sharp" /></template>
<style>
.zoe65kboz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.37 3.318C8.646 1.754 3 6.064 3 12a9 9 0 0 0 9 9c6.212 0 10.556-6.144 8.485-12M9 9h.01M15 9h.01M8 14a5.657 5.657 0 0 0 8 0m2-9h4");
}

</style>
