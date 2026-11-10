<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egr5h6g8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bridge-sharp" /></template>
<style>
.egr5h6g8y {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 3V7M6 7V16M6 7C7 9.5 9.5 11 12 11M6 7C5 8.5 4 9.5 2 10L1.243 10.189M6 16V21M6 16H1M6 16H12M12 11C14.5 11 17 9.5 18 7M12 11V16M12 16H18M18 7V3M18 7V16M18 7C19 8.5 20 9.5 22 10L22.757 10.189M18 16V21M18 16H23");
}

</style>
