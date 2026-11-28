<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk5wk15ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-check-plus-sharp" /></template>
<style>
.yk5wk15ye {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 22L12 22C6.4771 22 2 17.5228 2 12C2 6.4771 6.4771 2 12 2C17.5228 2 22 6.4771 22 12L22 13M19 15L19 23M15 19L23 19M7.7016 11.6644L10.6667 15L16.2984 8.6644");
}

</style>
