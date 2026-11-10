<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqk3sjdoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:light-max-sharp" /></template>
<style>
.sqk3sjdoz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 16H17M12 11V7M6.707 11.71L4.707 9.71M17.364 11.71L19.364 9.71M19 16H23M1 16H5");
}

</style>
