<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtxyddcvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:code-panel-sharp-fill" /></template>
<style>
.wtxyddcvh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 4L21 4L21 20L3 20L3 15M6.7279 3.6508L3 8L6.7279 12.3492M10.7007 3.6508L14.4286 8L10.7007 12.3492");
}

</style>
