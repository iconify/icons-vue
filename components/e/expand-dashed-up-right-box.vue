<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkyb-daam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-right-box" /></template>
<style>
.pkyb-daam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 13L6 3M9 6L6 3L3 6M11 18L21 18M18 21L21 18L18 15M16 3L18 3M21 6L21 8M18 11L16 11M13 6L13 8");
}

</style>
