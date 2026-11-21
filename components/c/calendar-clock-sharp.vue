<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6f8a0bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-clock-sharp" /></template>
<style>
.f6f8a0bxe {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.2889 21L3 21L3 5L21 5L21 8.2889M21 15.5C21 18.5376 18.5376 21 15.5 21C12.4624 21 10 18.5376 10 15.5C10 12.4624 12.4624 10 15.5 10C18.5376 10 21 12.4624 21 15.5ZM15 13.5L15 16L17.5 16M8 2L8 8M16 2L16 7.0147");
}

</style>
