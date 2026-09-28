<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu3zx5oba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-stock-up-sharp" /></template>
<style>
.gu3zx5oba {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 21L3 21L3 3ZM3 15L7 11L10 14L15 9L17 11L21 7");
}

</style>
