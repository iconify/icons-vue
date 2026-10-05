<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6yghabbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-up-fill" /></template>
<style>
.t6yghabbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 3L6 21M3 18L6 21L9 18M18 21L18 3M15 6L18 3L21 6");
}

</style>
