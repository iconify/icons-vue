<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-080hvge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headphones-sharp" /></template>
<style>
.g-080hvge {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12C3 10.8954 3.8954 10 5 10L7 10L7 21L5 21C3.8954 21 3 20.1046 3 19L3 12ZM21 12C21 10.8954 20.1046 10 19 10L17 10L17 21L19 21C20.1046 21 21 20.1046 21 19L21 12ZM3 12C3 7.0294 7.0294 3 12 3C16.9706 3 21 7.0294 21 12");
}

</style>
