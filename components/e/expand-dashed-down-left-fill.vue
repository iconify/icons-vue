<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7x96gbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-left-fill" /></template>
<style>
.g7x96gbnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 6L3 6M6 3L3 6L6 9M18 11L18 21M15 18L18 21L21 18M11 21L9.6667 21M5.6667 21C4.1939 21 3 19.8061 3 18.3333M3 14.3333L3 13");
}

</style>
