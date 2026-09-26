<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1tym-4tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:japanese-yen-sharp-two-tone" /></template>
<style>
.e1tym-4tt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.7526 1.7172L5 2L12 10L19 2L19.2474 1.7172M12 9L12 10L12 22L12 23M5 14L6 14L18 14L19 14M5 18L6 18L18 18L19 18");
}

</style>
