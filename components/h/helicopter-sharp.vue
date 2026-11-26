<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm9j2yrat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:helicopter-sharp" /></template>
<style>
.wm9j2yrat {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6L7 6L21 6L22 6M14 6L14 10M21.5207 14L16.5207 14L15.5207 14M7 10L19.2112 10L22 14.8303L22 18L11.6189 18ZM2 10L7 10M2 6L2 7L2 13L2 14");
}

</style>
