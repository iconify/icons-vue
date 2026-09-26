<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq4--5bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-left-box" /></template>
<style>
.xq4--5bem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 18L3 18M6 15L3 18L6 21M18 13L18 3M21 6L18 3L15 6M3 8L3 6M6 3L8 3M11 6L11 8M6 11L8 11");
}

</style>
