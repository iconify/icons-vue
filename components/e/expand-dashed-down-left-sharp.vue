<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlvzzwmpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-left-sharp" /></template>
<style>
.hlvzzwmpm {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 6L3 6M6.2929 2.7071L3 6L6.2929 9.2929M18 10L18 21M14.7071 17.7071L18 21L21.2929 17.7071M12 21L8.6667 21M6.6667 21L3 21L3 17.3333M3 15.3333L3 12");
}

</style>
