<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="budiujh_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hamburger-sharp" /></template>
<style>
.budiujh_s {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 12L4 11C4 6.5817 7.5817 3 12 3C16.4183 3 20 6.5817 20 11L20 12M2 12L22 12L22 16L2 16ZM4 16L4 21L20 21L20 16");
}

</style>
