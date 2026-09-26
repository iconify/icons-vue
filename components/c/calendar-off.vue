<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1edoac6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-off" /></template>
<style>
.f1edoac6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.6569 5L18 5C19.6568 5 21 6.3431 21 8L21 15.3431M20.1213 20.1213C19.5785 20.6642 18.8285 21 18 21L6 21C4.3431 21 3 19.6569 3 18L3 8C3 6.6462 3.8967 5.5019 5.1285 5.1285M7 11L11 11M16 3L16 7M2 2L22 22");
}

</style>
