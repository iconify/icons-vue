<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbtd6b36l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-distribute-center-sharp" /></template>
<style>
.hbtd6b36l {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17V14H17V17M7 17V20H17V17M7 17H1M17 17H23M19 7V10H5V7M19 7V4H5V7M19 7H23M5 7H1");
}

</style>
