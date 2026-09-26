<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uht88ogek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-off-sharp" /></template>
<style>
.uht88ogek {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.6569 5L21 5L21 16.3431M21 21L3 21L3 5L5 5M6 11L11 11M16 2L16 8M1.7071 1.7071L22.2929 22.2929");
}

</style>
