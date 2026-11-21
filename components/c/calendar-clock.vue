<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbd-su4-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-clock" /></template>
<style>
.gbd-su4-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.754 21L6 21C4.3431 21 3 19.6569 3 18L3 8C3 6.3431 4.3431 5 6 5L18 5C19.5587 5 20.8578 6.1937 20.9893 7.7469M21 15.5C21 18.5376 18.5376 21 15.5 21C12.4624 21 10 18.5376 10 15.5C10 12.4624 12.4624 10 15.5 10C18.5376 10 21 12.4624 21 15.5ZM15 14.1V16H16.9M8 3V7M16 3V6.0132");
}

</style>
