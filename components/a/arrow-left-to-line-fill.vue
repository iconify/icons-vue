<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo8z2_blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-left-to-line-fill" /></template>
<style>
.xo8z2_blj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 12H6.9413M12.8771 5L6.1739 11.587C5.942 11.815 5.942 12.185 6.1739 12.413L12.8771 19M2 5V19");
}

</style>
