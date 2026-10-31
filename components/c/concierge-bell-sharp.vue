<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh0qrqbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:concierge-bell-sharp" /></template>
<style>
.gh0qrqbjj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 15L22 15L22 21L2 21ZM4 15C4 10.5817 7.5817 7 12 7C16.4183 7 20 10.5817 20 15M12 7L12 3M8 3L16 3");
}

</style>
