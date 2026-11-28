<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dutf2lyxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-clock-sharp" /></template>
<style>
.dutf2lyxf {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 10L5.5 6.5C5.5 4.0147 7.5147 2 10 2C12.4853 2 14.5 4.0147 14.5 6.5L14.5 8M10.5 10L2 10L2 22L9.5 22M22 16.5C22 19.5376 19.5376 22 16.5 22C13.4624 22 11 19.5376 11 16.5C11 13.4624 13.4624 11 16.5 11C19.5376 11 22 13.4624 22 16.5ZM16 14.1L16 17L18.9 17");
}

</style>
