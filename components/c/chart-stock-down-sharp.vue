<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erx5muytk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-stock-down-sharp" /></template>
<style>
.erx5muytk {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 21L3 21L3 3ZM3 9L7 13L10 10L15 15L17 13L21 17");
}

</style>
