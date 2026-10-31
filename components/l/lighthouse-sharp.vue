<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i44i3ibpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lighthouse-sharp" /></template>
<style>
.i44i3ibpq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9L9 5L12 2L15 5L15 9ZM9 5L15 5M6 9L18 9M9 9L7 22M15 9L17 22M8.3846 13L15.6154 13M7.6923 17.5L16.3077 17.5M3 22L21 22M22.5528 2.7236L19.4472 4.2764M19.4472 13.7236L22.5528 15.2764M20 9L23 9M1.4472 2.7236L4.5528 4.2764M4.5528 13.7236L1.4472 15.2764M4 9L1 9");
}

</style>
