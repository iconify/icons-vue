<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1u4p_b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:handbag-search" /></template>
<style>
.o1u4p_b3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7C8 4.790861 9.790861 3 12 3C14.209139 3 16 4.790861 16 7M10 21L7 21C5.3431 21 4 19.6569 4 18L4 10C4 8.3431 5.3431 7 7 7L17 7C18.6569 7 20 8.3431 20 10L20 11M19 17.5C19 18.8807 17.8807 20 16.5 20C15.1193 20 14 18.8807 14 17.5C14 16.1193 15.1193 15 16.5 15C17.8807 15 19 16.1193 19 17.5ZM18.5 19.5L20 21");
}

</style>
