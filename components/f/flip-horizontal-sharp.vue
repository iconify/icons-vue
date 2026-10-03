<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7g_5_9ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-horizontal-sharp" /></template>
<style>
.o7g_5_9ji {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.9999 7.0001L8 12L1.9999 16.9999L1.9999 7.0001ZM22.0001 7.0001L16.0001 12L22.0001 16.9999L22.0001 7.0001ZM12 1L12 5M12 7L12 11M12 13L12 17M12 19L12 23");
}

</style>
