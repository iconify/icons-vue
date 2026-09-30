<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqcotpbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:landmark-sharp" /></template>
<style>
.zqcotpbzo {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8L21 8L12 3L3 8ZM6 11L6 18M12 11L12 18M18 11L18 18M2 21L22 21");
}

</style>
